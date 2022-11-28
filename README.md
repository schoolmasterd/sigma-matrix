# sigma-matrix
Matrix for computing Carp pop dyn in Illinois River

 The A' matrix used in Schoolmaster et al.: Potential Pool-Scale and River-scale Effects of Non-Physical Deterrent Barriers on Invasive Carp in the Illinois River 
 
 This package contains a single function that takes as arguments a set of movment probabilites and a recruitment rate:
(q12, q23, q34, q45, q56, q21, q32, q43, q54, q65, b0), where q_xy is the monthly movment probability from pool x to pool y and b0 is the recruitment rate in pools 4-6. See manucript for details. 
