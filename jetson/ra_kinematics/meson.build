project('ra_kinematics', 'cpp', default_options : ['cpp_std=gnu++1z', 'buildtype=release'])
# project('ra_kinematics', 'cpp', default_options : ['cpp_std=c++1z'])

liblcm = dependency('lcm')

executable('jetson_ra_kinematics', 'main.cpp', 'arm_state.cpp', 'kinematics.cpp', 'utils.cpp', 'mrover_arm.cpp', 'motion_planner.cpp',
           dependencies : [liblcm],
           install : true)
