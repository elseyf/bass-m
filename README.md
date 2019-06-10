# bass-m
A modified version of the bass assembler by byuu (using the updated version by ARM9 https://github.com/ARM9/bass)

Modifications: \
    - Using a more convenient syntax for GameBoy (removed the first argument of any 8-Bit arithmetic instruction, because it could only be A) \
    - Added an internal function called 'fp8()'; this will create a fixed-point number in 8.8-Bit format \

See README.original for compilation instructions
