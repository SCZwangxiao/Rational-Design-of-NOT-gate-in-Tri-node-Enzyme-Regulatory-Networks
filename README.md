# code
Introduction
--
This software is free, open source software released under the GNU General Public License.

This is an software for finding tri-node enzyme regulatory networks that perform NOT-gate function. The software expects as input network topology data, and ouputs all evalution index. Briefly, it works in two steps: first, it
examines all possible networks and calculates their responsive curves. Then, it calculate evalution index based on the curves.

This software can be easily modified to calculate your evalution index.

This software is free to use, modify, redistribute without any restrictions, except including the license provided with the distribution. 

Prerequisites
--
You must have numerical compuation library called GUN Scientific Library (GSL) v2.5 or its higher version. You can install it using file "gsl-2.5.tar.gz".

Compile
--
Go into the project directory, and compile the project.

```
cd code
./makefile
```
Run Code
--

```
./run.sh
```
