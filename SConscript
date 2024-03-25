from building import *

cwd = GetCurrentDir()
src = Glob('*.c') + Glob('*.cpp')
inc = [cwd]

group = DefineGroup('Jarzebski-MPU6050', src, depend = ['PKG_USING_ARDUINO_JARZEBSKI_MPU6050'], CPPPATH = inc)

Return('group')
