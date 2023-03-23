# OIBSIP
package umldigram;

public class Airport {
	
 static String airport="International Airport";
   
 Ticket t;
 User u;
 
 public void BookTicket(User u,Ticket t) {
	 
	 if(this.u==null) {
		 
		 this.u=u;
		 System.out.println("user is created");
		 if(this.t==null) {
			 
			 this.t=t;
			 System.out.println("Ticket has Booked");
		 }
		 else {
			 System.out.println("Ticket has already booked");
		 }}
		 
		 else {
			 
			 System.out.println("User is already present");
			 
		 }
	 }
	 
	public void ticketDetails(int ticketNo) {
		
		if(this.t!=null&&this.u!=null) {
			if(t.getTicketNo()== ticketNo) {
				u.userDetails();
				t.ticketDetails();
			}else {
			  System.out.println("no ticket found");
			}}
				
			else {
				System.out.println(" no user is found  and no ticket is found");
			}
			
			}
	
	public void cancelTicket( int ticketNo) {
		
		if(this.u!=null&&this.t!=null) {
			
			if(t.getTicketNo()==ticketNo) {
				
				this.t=null;
				System.out.println("Ticket has cancelled");
				
				
				
			}
			else {
				System.out.println("ticket number is not macthing");
		}
			
		
		
	}
		else {
			System.out.println(" no user is found  and no ticket is found");
		}	
	}
	
	public void modififyTicket( int ticketNo,String boarding,String destination) {
		
		                      if(this.t!=null&&this.u!=null) {
		                    	  
		                    	  if(t.getTicketNo()==ticketNo) {
		                    		  t.setBoarding(boarding);
		                    		  t.setDestination(destination);
		                              }
		                    	  else {
		                    		  System.out.println("ticket number not matching");
		                    	  }
		                    	  
		                      }
		                      else {
		                    	  System.out.println("no user is found  and no ticket is found");
		                      }
		
	}

	 
		
	}
	
 

