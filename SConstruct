#!/usr/bin/python

import os

VariantDir('build', 'src', duplicate=0)

env = Environment(ENV=os.environ)
Tool('mingw')(env)

env.Program('build/lines.cpp')

#
# vim: set expandtab tabstop=4 shiftwidth=4 syntax=python:
#

