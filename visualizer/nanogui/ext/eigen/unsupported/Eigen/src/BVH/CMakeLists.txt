FILE(GLOB Eigen_BVH_SRCS "*.h")

INSTALL(FILES
  ${Eigen_BVH_SRCS}
  DESTINATION ${INCLUDE_INSTALL_DIR}/unsupported/Eigen/src/BVH COMPONENT Devel
  )
