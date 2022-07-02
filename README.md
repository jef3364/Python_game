# Python_game: 利用pygame module自己創造的小遊戲

### 參考資料
  * 1.Pygame Page: http://pygame.org
  * 2.documentation: http://pygame.org/docs/ref/
  * 3.Icon Archive: https://iconnarchive.com/
  * 4.Leshy SFMaker: https://www.leshylabs.com/apps/sfMaker/
  * 5.Font Space: https://www.fontspace.com/commercial-fonts
  * 6.Game Art 2D: https://www.gameart2d.com/freebies.html
  * 7.Open Game Art.org: https://opengameart.org/
  * 8.Freepik: https://www.freepik.com/free-photos-vectors/game-background
  * 9.Chosic: https://www.chosic.com/free-music/games/<br><br><br>
 -----------

### What is Pygame:
  * Pygame提供Display,Sound,Image,Text,Event幫助製作遊戲
  * Pygame可以做出2-D小遊戲
  * Pygame偵測使用者使用Keyboard,joystsick,mouse控制遊戲
  * Pygame提供許多內建的game object來製作遊戲<br><br><br>
 ------------
### Pygame Basics:
| name | Description |
|:-----:|:----------:|
|_p1.py_| Create my game surface,game loop and drawing. |
|_p2.py_| Blit text, font, sound and image objects.  |
|_FEED.py_| Getting user keyboard and collision dection. |

### Code snippet
```python
#Create game display
WINDOW_WIDTH, WINDOW_HEIGHT = 1200, 600
displayscreen = pygame.display.set_mode((WINDOW_WIDTH,WINDOW_HEIGHT))
pygame.display.set_caption("Feed the Angry Bird!")

```
```python
#Blit image obkect and settings its rec.
player_image = pygame.image.load("angry_bird.png")
player_rect = player_image.get_rect()
player_rect.left = 32
player_rect.centery = WINDOW_HEIGHT//2
displayscreen.blit(player_image,player_rect)
```
### Game Assets:
  * [Icon Archive:](https://iconnarchive.com/)網站提供很多遊戲角色下載
  * [Leshy SFMaker:](https://www.leshylabs.com/apps/sfMaker/)網站可以下載遊戲特效，也可以簡單自己製作音效
 
![2.py](https://raw.githubusercontent.com/jef3364/Python_game/main/%E6%88%AA%E5%9C%96.png)


