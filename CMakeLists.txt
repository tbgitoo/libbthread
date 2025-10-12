add_library(libbtrhead
        SHARED
        pt-cancel.c
        pt-docancel.c
        pt-init.c
        pt-setcancelstate.c
        pt-setcanceltype.c

)

target_link_libraries(libbtrhead -lz -ldl -lm)
