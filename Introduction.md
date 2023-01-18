


# State equations:
$ p_k = p_{k-1} + dt +a_{k-1} * dt^2/2 $  
$ v_k = v_{k-1} + a_{k-1}*dt $  
$ q_k = q_{k-1} \otimes q(\omega_{k-1},dt) $  

here, $p_k$ represents the postion of the vehicle in the 3D space  
$v_k$ represents the velocity of the vehicle in the 3D space  
$q_k$ represents the orientation of the vehicle in form of a quaternion  
