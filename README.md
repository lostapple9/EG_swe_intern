# Colab Link
https://colab.research.google.com/drive/1mvhNibXkmLvOfdGMmyqNOwXpMQMS0vBd?usp=sharing

# Evil_Genius

3. (No Coding) Most of the time, our stakeholders (in this case, the CS:GO
coaching staff) aren’t tech-savvy enough to run code themselves. Propose a
solution to your product manager that:

a. could allow our coaching staff to request or acquire the output themselves

we could made it a scrip py file and run it in cmd with inputs from the staff.

b. takes less than 1 weeks worth of work to implement

  We just need to add a user py file with import from the ProcessGameState py file.
	
  For example:
	
    we have:
		
      Enter 1 to 3 for options:
			
        1. Extract the weapon classes from the inventory json column
				
        2. Is entering via the light blue boundary a common strategy used by Team2 on T (terrorist) side?
				
	    3. end
					
       Lets say user enter 1.
			 
       output:
			 
        {'Grenade', 'Pistols', 'Rifle', 'SMG'}
				
        end? (y/n):
				
        y
				
     Then the script ends

        
