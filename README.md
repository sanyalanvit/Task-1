import tensorflow as tf # 1
 
a = tf.constant(1) # 2
b = tf.constant(2) # 3
 
c = tf.add(a, b) # 4
 
with tf.Session() as sess: # 5
    print(sess.run(c)) # 6
