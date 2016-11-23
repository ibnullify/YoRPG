public abstract class Character{
    protected int hp;
    protected int strength;
    protected int defense;
    protected double attackrating;

    protected boolean isAlive(){
	if (hp <= 0){
	    return false;
	}
	return true;
    }

    protected int getDefense(){
	return defense;

    }
	
	protected String getName(){
	return "";
	}
	



    protected void lowerHP(int ssubtractThis){
	hp = hp - ssubtractThis;
    }

    protected int attack(Character toAttack){
	int damage = (int)(strength * attackrating) - toAttack.getDefense();
	if (damage < 0){ damage = 0;}
	toAttack.lowerHP(damage);
	return damage;
    }
	
	protected abstract String about();
    protected abstract void specialize();
    protected abstract void normalize();
   
}
