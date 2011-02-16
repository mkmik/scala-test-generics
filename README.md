This test reproduces http://lampsvn.epfl.ch/trac/scala/ticket/4067


1. You can build with ant. The code compiles.

2. You can import the project in eclipse. The build should fail.

3. Switch the scala library with "ant fix" and reload the project (F5) in eclipse (Possibly a couple of times). The build should succeed.

4. You can revert with "ant original" 

