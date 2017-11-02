_G.AutoCarry_Version -- number
_G.AutoCarry_Loaded -- bool

Callbacks :
OnBeforeAttack(function(target) ..
OnAttack(function(unit, target) ..
OnAfterAttack(function(unit, target) ..
OnTargetChange(function(oldtarget, newtarget) ..
OnNonKillableMinion(function(minion) ..

Vars and Funcs:
DACR.LastAttackTime -- return Last Attack Time (ms)
DACR.attacksEnabled -- Set Attacks (true/false)
DACR.movementEnabled -- Set Movements (true/false)
DACR.LastMovePosition -- return Vector3D
DACR.LastTarget -- return Unit (can be nil)
DACR.missileLaunched -- true/false if missile is launched (Attack Land on Melees)
DACR.forceTarget -- Set Unit for forcing orbwalk target/nil for unforcing
DACR.forcePos -- Set Vec3D for forcing orbwalk position/nil for unforcing
DACR:Mode() -- return one of the 5 modes : "Combo", "Harass", "LaneClear", "LastHit", "Freeze"
DACR:GetTarget() -- return current target (can be nil)
DACR:GetProjectileSpeed(unit) -- return projectile speed of unit
DACR:GetHealthPrediction(unit, time, delay) -- return predicted health of unit after time+delay
DACR:GetAutoAttackDamage(unit,target,includebonuscalcs) -- 3rd Param is boolean, return damage
DACR:GetAnimationTime(unit) -- return unit animation time (s)
DACR:CanAttack() -- true/false if can attack
DACR:CanMove() -- true/false if can move
DACR:ResetAA() -- Reset AA
DACR:ForceTarget(unit) -- Set Unit for forcing orbwalk target/nil for unforcing
DACR:ForcePos(Vec3D) -- Set Vec3D for forcing orbwalk position/nil for unforcing
