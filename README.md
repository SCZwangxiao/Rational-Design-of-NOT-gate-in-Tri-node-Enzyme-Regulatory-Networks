# Code
Introduction
--
This software is free, open source software released under the GNU General Public License.

This is an software for finding tri-node enzyme regulatory networks that perform NOT-gate function. The software expects as input network topology data, and ouputs all evalution index. Briefly, it works in two steps: first, it
examines all possible networks and calculates their responsive curves. Then, it calculate evalution index based on the curves.

This software can be easily modified to calculate your evalution index.

Copyright (C) <2019>  Shandong University

This program is licensed under the GNU General Public License 3.0 (https://www.gnu.org/licenses/gpl-3.0.html). Any derivative work obtained under this license must be licensed under the GNU General Public License as published by the Free Software Foundation, either Version 3 of the License, or (at your option) any later version, if this derivative work is distributed to a third party.

The copyright for the program is owned by Shandong University. For commercial projects that require the ability to distribute the code of this program as part of a program that cannot be distributed under the GNU General Public License, please contact <scz.wangxiao@gmail.com> to purchase a commercial license.

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
