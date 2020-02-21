Things to get done
--

Files to rewrite:
- [X] Main.php 
- [X] VehicleType.php
- [X] Factory.php
- [X] VehicleBase.php
- [X] Vehicle.php
- [X] CommandHandler.php
- [X] EventHandler.php
- [ ] **CLEANUP**


Vehicle NBT Structure (not including base entity data):

```
CompoundTag EntityNBT
 - vehicle(int) (Vehicle Version)
 - VehicleData(CompundTag)
   - type(int)
   - name(string)
   - design(string)
   - gravity(float)
   - scale(float)
   - baseOffset(float)
   - forwardSpeeed(float)
   - backwardSpeed(float)
   - leftSpeed(float)
   - rightSpeed(float)
   - bbox(ListTag)
     - x(float)
     - y(float)
     - z(float)
     - x2(float)
     - y2(float)
     - z2(float)
   - driverSeat(ListTag)
     - x(float)
     - y(float)
     - z(float)
   - passengerSeats(ListTag)
     - (ListTag) x How many seats there are
       - x(float)
       - y(float)
       - z(float)
```