# pygame
import pygame
pygame.init()    
while True:
  event=pygame.event.poll()
  if event.type == pygame.QUIT:
      break
pygame.quit()
