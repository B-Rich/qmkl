add_library (
	blas
	OBJECT
		gemm.c
		copy.c
)

qasm2m4_dep_on_c (gemm.c sgemm)
qasm2m4_dep_on_c (copy.c scopy)
