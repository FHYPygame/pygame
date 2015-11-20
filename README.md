# pygame
import pygame
a=3
print a
pygame.init()    
while True:
  event=pygame.event.poll()
  if event.type == pygame.QUIT:
      break
pygame.quit()
