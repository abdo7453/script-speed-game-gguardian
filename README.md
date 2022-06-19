# script-speed-game-gguardian
This script speed all games for game gguardian
-------------lobby------------"
function START()
vip = gg.choice({
	"speed 1",
"speed 1.2",
"speed 3",
"speed 5",
"speed. 15",
"              ❗🚪EXIT🚪❗",
},nil,"1")


 if vip == nil then else end
if vip == 1 then A1() end 
if vip == 1 then A2() end
if vip == 1 then A3() end
 if vip == 1 then A4() end
 if vip == 2 then Exit() end





function A1()
gg.setSpeed(1)
gg.toast("SPEED NR")
end 









function A2()
gg.setSpeed(1.2)
gg.toast("SPEED LOW ")
end 











function A3()
gg.setSpeed(3)
gg.toast("SPEED LW ")
end 







function A4()
gg.setSpeed(5)
gg.toast("SPEED 5")
end 












function A2()
gg.setSpeed(15)
gg.toast("SPEED 15 ")
end 





end
function Exit()  
  print("☆➡️➡️➡️➡️➡️➡️➡️➡️➡️➡️")
  print("    ↘️↘️↘️↘️↘️↘️↘️↘️  ")
  print("       ↗️↗️↗️↗️↗️↗️  ")
  print("          ❓❓❓❓")
 
os.exit()
end
 
while true do
  if gg.isVisible(true) then
    menuk = 1
    gg.setVisible(false)
  end
  if menuk == 1 then
    START()
  end
  if menu == 2 then
      START()
    end
  menuk = -1
end
