set(SOURCES
    allocate_sendrecv.f90
    bisection.f90
    calc_allob.f90
    calcELF.f90
    calc_force_c.f90
    calc_force.f90
    calc_gradient_fast_c.f90
    calc_gradient_fast.f90
    calc_iquotient.f90
    calc_iroot.f90
    calcJxyz.f90
    calcJxyz_all.f90
    calcJxyz_all_periodic.f90
    calc_myob.f90
    calc_ob_num.f90
    calc_pmax.f90
    calcuV.f90
    calcVpsl.f90
    calcVpsl_periodic.f90
    check_cep.f90
    check_corrkob.f90
    check_mg.f90
    check_ng.f90
    check_numcpu.f90
    conv_p0.f90
    conv_p.f90
    exc_cor_ns.f90
    hartree_boundary.f90
    hartree_cg.f90
    hartree_periodic.f90
    hartree.f90
    init_wf.f90
    init_k_rd.f90
    inner_product3.f90
    inner_product4.f90
    laplacianh.f90
    nabla.f90
    OUT_IN_data.f90
    psl.f90
    read_copy_pot.f90
    sendrecv_copy.f90
    setbN.f90
    setcN.f90
    set_filename.f90
    set_gridcoo.f90
    set_icoo1d.f90
    set_imesh_oddeven.f90
    set_ispin.f90
    set_isstaend.f90
    storevpp.f90
    total_energy_periodic.f90
    writeavs.f90
    writecube.f90
    writedns.f90
    writeelf.f90
    writeestatic.f90
    writepsi.f90
    writevtk.f90
    ylm.f90
    )

add_library(${GCEED_COMMON_LIB} ${SOURCES})
add_dependencies(${GCEED_COMMON_LIB} ${GCEED_MODULE_LIB})
