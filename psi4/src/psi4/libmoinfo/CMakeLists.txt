list(APPEND sources
  model_space.cc
  model_space_build.cc
  moinfo.cc
  moinfo_base.cc
  moinfo_mappings.cc
  moinfo_model_space.cc
  moinfo_scf.cc
  moinfo_slaterdeterminant.cc
  slater_determinant.cc
  )
psi4_add_module(lib moinfo sources)
