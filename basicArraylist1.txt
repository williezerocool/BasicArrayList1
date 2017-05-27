/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package basicarraylists1;

import java.util.ArrayList;
/**
 *
 * @author kendrabooker
 */
public class BasicArraylists1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
     
        ArrayList<Integer> arrList = new ArrayList<>();
        
       do{
       
           arrList.add(-113);
       }while(arrList.size() < 10);
       
       for(int i=0; i<arrList.size(); i++){
       
           System.out.println("Slot " + i + " contains " + arrList.get(i));
       }
       
      
    
    
    }
 }
