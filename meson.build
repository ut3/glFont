# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright 2020 J Rick Ramstetter, rick@anteaterllc.com
# 
# This file is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License, version 2 
# as published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.

project('glfont', 'c')

gl_dep = dependency('gl')

glfont = shared_library('glfont', 'glfont.c', dependencies: gl_dep)

inc = include_directories('.')
glfont_dep = declare_dependency(link_with : glfont, include_directories: inc)
