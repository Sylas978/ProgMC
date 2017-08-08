# ProgMC
from mcpi.minecraft import Minecraft
import random
from time import sleep
mc = Minecraft.create()
x, y, z = mc.player.getPos()
#prints = 0
#mc.setting("nametags_visible", True)
while 1 + 0 > 0:
    x, y, z = mc.player.getPos()
    corx = random.randint(28, 48)
    corz = random.randint(19, 39)
    mc.player.setPos(0 - corx, 1, corz)
    mc.setBlock(x, y-1, z, 246)
#    if prints == 4:
#        mc.postToChat("SLENDERMAN")
#        prints = 0
#    prints += 1
    sleep(0.5)
