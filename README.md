# Patika.dev Insertion Sort

* Patika Profil Linki:  https://app.patika.dev/sakas

## Ödev 


* [22,27,16,2,18,6]

 1. Yukarıda verilen dizinin insertion sort türüne göre aşamalarını yazınız.
 
    *  Sorting Öncesi - [22, 27, 16, 2, 18, 6]
 
        * Step 1
        
          ֎ 2. elemandan başlanır, solundaki sayıyla karşılaştılır, 27>22 olduğu için aynen kalır. [22, 27, 16, 2, 18, 6]
         
        * Step 2 
          
          ֎ 3. elemana geçilir, solundaki sayıyla karşılaştırılır, 16<27 olduğu için 1 sıra sola kaydırılır -> [22, 16, 27, 2, 18, 6]
          
          ֎ 2. sıraya yerleşen sayı solundaki sayıyla karşılaştırılır, 16<22 olduğu için 1 sıra sola kaydırılır -> [16, 22, 27, 2, 18, 6]
         
        * Step 3
        
          ֎ 4. elemana geçilir, solundaki sayıyla karşılaştırılır, 2<27 olduğu için 1 sıra sola kaydırılır -> [16, 22, 2, 27, 18, 6]  
          
          ֎ 3. sıraya yerleşen sayı solundaki sayıyla karşılaştırılır, 2<22 olduğu için 1 sıra sola kaydırılır -> [16, 2, 22, 27, 18, 6]
          
          ֎ 2. sıraya yerleşen sayı solundaki sayıyla karşılaştırılır, 2<16 olduğu için 1 sıra sola kaydırılır -> [2, 16, 22, 27, 18, 6]
         
        * Step 4
        
          ֎ 5. elemana geçilir, solundaki sayıyla karşılaştırılır, 18<27 olduğu için 1 sıra sola kaydırılır -> [2, 16, 22, 18, 27, 6]  
          
          ֎ 4. sıraya yerleşen sayı solundaki sayıyla karşılaştırılır, 18<22 olduğu için 1 sıra sola kaydırılır -> [2, 16, 18, 22, 27, 6]  
          
          ֎ 3. sıraya yerleşen sayı solundaki sayıyla karşılaştırılır, 18>16 olduğu için aynen kalır -> [2, 16, 18, 22, 27, 6]
         
        * Step 5 - [2, 6, 16, 18, 22, 27]
        
          ֎ 6. elemana geçilir, solundaki sayıyla karşılaştırılır, 6<27 olduğu için 1 sıra sola kaydırılır -> [2, 16, 18, 22, 6, 27]  
          
          ֎ 5. sıraya yerleşen sayı solundaki sayıyla karşılaştırılır, 6<22 olduğu için 1 sıra sola kaydırılır -> [2, 16, 18, 6, 22, 27]  
          
          ֎ 4. sıraya yerleşen sayı solundaki sayıyla karşılaştırılır, 6<18 olduğu için 1 sıra sola kaydırılır -> [2, 16, 6, 18, 22, 27]  
          
          ֎ 3. sıraya yerleşen sayı solundaki sayıyla karşılaştırılır, 6<16 olduğu için 1 sıra sola kaydırılır -> [2, 6, 16, 18, 22, 27]  
           
          ֎ 2. sıraya yerleşen sayı solundaki sayıyla karşılaştırılır, 6>2 olduğu için aynen kalır -> [2, 6, 16, 18, 22, 27]  
          
     * Sorting Sonrası - [2, 6, 16, 18, 22, 27]   
 
 2. Big-O gösterimini yazınız.
 
    * O(n²)

 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    * Average Case: 16, 18
    
    * Worst Case: 27
    
    * Best Case: 2

 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 
    * Average Case

 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    
    * Step 1 - [3, 7, 5, 8, 2, 9, 4, 15, 6]

    * Step 2 - [3, 5, 7, 8, 2, 9, 4, 15, 6]
    
    * Step 3 - [3, 5, 7, 8, 2, 9, 4, 15, 6]
    
    * Step 4 - [2, 3, 5, 7, 8, 9, 4, 15, 6]
    
