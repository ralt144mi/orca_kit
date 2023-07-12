# orca structures

ORCA code structures for various tasks 

clock.tempo=80

Pa*d('music', speed ='1 2', legato=2, p=.5, )

Pi*d('.hardkick:3!3.notes', room=1, speed='7 3', size=.1, scram=.6, lpf=133')

Pg*n('E4 [B5 G3] G1')

Pd * d('bd', p=.25, 
       n="[D4 F4]+(2|7|12)", pan='rand', 
       amp='0.02~0.1', leg=1.9, release='0.1~0.3',
       oct=4, speed="{1 0.99}",
)

pg.stop()
silence()

()