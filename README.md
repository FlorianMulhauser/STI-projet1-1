#   S T I - p r o j e t 1  
  
  
 I m p o r t a n t   :    
     *   a j o u t e r   ` 1 2 7 . 0 . 0 . 1   s t i `   a u   f i c h i e r   :    
         *   ` % S y s t e m R o o t % \ S y s t e m 3 2 \ d r i v e r s \ e t c \ h o s t s `   s u r   W i n d o w s  
         *   ` / e t c / h o s t s `   s u r   l i n u x  
          
          
          
          
 # #   U s e r s  
  
  
  
 |   u s e r n a m e     |   p a s s w o r d     |   r o l e     |   a c t i v e     |  
 | - - - | - - - | - - - | - - - |  
 |   u s e r 1     |   a s d     |   C o l l a b o r a t o r     |   '    |  
 A d m i n i s t r a t o r | I A m T h e A l p h a A n d T h e O m e g a | A d m i n i s t r a t o r | ' 
 T e s t | T e s t | A d m i n i s t r a t o r | L' 
 a s d | a s d | C o l l a b o r a t o r | L' 
 a s d a s d | a s d | C o l l a b o r a t o r | ' 
 q w e | q w e | C o l l a b o r a t o r | ' 
 J o h n | p a s s w o r d | C o l l a b o r a t o r | ' 
 C a s h e w | s a l t | A d m i n i s t r a t o r | L' 
 C a r o l i n e | 2 2 1 2 0 5 | C o l l a b o r a t o r | ' 
 G r e g | T h e G r e g g i n a t o r | C o l l a b o r a t o r | ' 
 B o b | L e B r i c o l e u r | C o l l a b o r a t o r | ' 
 J e a n - H e n r y | y x c | C o l l a b o r a t o r | ' 
  
  
  
 # #   P a g e s  
  
 -   * * l o g i n . p h p * *  
  
 T h i s   p a g e   c o n t a i n s   t h e   c o d e   r e t r i e v i n g   t h e   i n f o r m a t i o n   r e g a r d i n g   t h e   u s e r   t r y i n g   t o   l o g   i n   t h e   w e b s i t e .   T h i s   c o d e   w i l l   t h e n   v e r i f y   t h e   a c c u r a c y   o f   t h e   p a s s w o r d   u s e d   a n d   i f   i t   i s   r i g h t ,   t h e   s e s s i o n   i s   s e t   a n d   t h e   u s e r   i s   r e d i r e c t e d   t o   t h e   p a g e   " i n d e x . p h p " .   I f   t h e   u s e r n a m e   o r   t h e   p a s s w o r d   i s   w r o n g ,   a n   e r r o r   w i l l   a p p e a r   o n   s c r e e n   t e l l i n g   t h e   u s e r   t o   c h e c k   h i s   c r e d e n t i a l s .   I f   t h e   a c c o u n t   i s   d i s a b l e d ,   t h e   u s e r   w i l l   n o t   b e   a b l e   t o   l o g   i n .    
  
 -   * * i n d e x . p h p * *  
  
 T h i s   p a g e   d o e s   n o t   d o   a n y t h i n g   s p e c i a l   e x c e p t   w e l c o m i n g   t h e   u s e r   a n d   d i s p l a y i n g   t h e   f e a t u r e s   h e   c a n   u s e   :   t h e   m a i l b o x ,   t h e   s e t t i n g s   a n d   t h e   " l o g o u t "   b u t t o n .  
  
 -   * * m a i l b o x . p h p * *  
  
 W h e n   t h e   u s e r   c l i c k s   o n   t h e   " m a i l b o x "   b u t t o n   o n   t h e   " i n d e x . p h p "   p a g e ,   i t   r e d i r e c t s   h i m   o n   t h i s   v e r y   p a g e ,   w h e r e   a l l   t h e   m e s s a g e s   h e   r e c e i v e d   a r e   d i s p l a y e d .   H e   c a n   t h e n   c h o o s e   w h a t   t o   d o   w i t h   t h o s e   m e s s a g e s   :   r e a d   t h e m ,   r e p l y   t o   t h e m   o r   d e l e t e   t h e m .    
  
 T h e   c o d e   i n   t h i s   p a g e   i n t e r p r e t s   t h e   u s e r ' s   i n p u t s .   I f   t h e   u s e r   d o e s   n o t   c l i c k   a n y   b u t t o n ,   t h e   d i s p l a y   d o e s   n o t   c h a n g e .  
  
 W h e n   t h e   u s e r   c l i c k s   o n   " R e a d " ,   t h e   c o d e   d i s p l a y s   t h e   m e s s a g e ' s   i n f o r m a t i o n s   ( a u t h o r ,   s u b j e c t ,   d a t e )   a n d   a l s o   d i s p l a y s   t w o   b u t t o n s   t o   e i t h e r   r e p l y   o r   d e l e t e   t h e   m e s s a g e .   W h e n   t h e   u s e r   c l i c k s   o n   " R e p l y " ,   t h e   c o d e   d i s p l a y s   a n   i n p u t   b o x   a n d   b e l o w ,   t h e   m e s s a g e   b e i n g   r e p l i e d   t o .   W h e n   t h e   u s e r   c l i c k s   o n   " D e l e t e " ,   t h e   c o d e   r e d i r e c t s   h i m   t o   t h e   p a g e   " d e l e t e _ m s g . p h p " .    
  
 T h e   u s e r   c a n   a l s o   c h o o s e   t o   w r i t e   a   n e w   m e s s a g e   b y   c l i c k i n g   o n   t h e   " W r i t e   n e w "   b u t t o n .   T o   w r i t e   a   n e w   m e s s a g e ,   h e   h a s   t o   e n t e r   a   v a l i d   u s e r   e x i s t i n g   i n   t h e   d a t a b a s e ,   a   s u b j e c t   a n d   t h e   t e x t   f o r   h i s   m e s s a g e .   O n c e   h e   c l i c k s   t h e   b u t t o n   " S e n d " ,   t h e   c o d e   i n s e r t s   t h e   m e s s a g e   i n   t h e   d a t a b a s e .    
  
 -   * * d e l e t e _ m s g . p h p * *  
  
 T h i s   p a g e   c o n t a i n s   t h e   c o d e   t h a t   e f f e c t i v e l y   d e l e t e s   t h e   m e s s a g e   f r o m   t h e   d a t a b a s e   a n d   t h e n   r e d i r e c t s   t h e   u s e r   t o   t h e   m a i l b o x   p a g e .  
  
 -   * * s e t t i n g s . p h p * *  
  
 T h i s   p a g e   a l l o w s   t h e   u s e r   t o   c h a n g e   h i s   p a s s w o r d .   I n   o r d e r   t o   d o   t h i s ,   h e   m u s t   e n t e r   c o r r e c t l y   h i s   c u r r e n t   p a s s w o r d ,   w h i c h   i s   v e r i f i e d   i n   t h e   d a t a b a s e .   H e   m u s t   t h e n   e n t e r   a   n e w   p a s s w o r d   a n d   c o n f i r m   i t .   T h e   p a s s w o r d   m u s t   b e   n e w   a n d   t h e   c o n f i r m a t i o n   m u s t   b e   c o r r e c t .   W h e n   t h e   u s e r   c l i c k s   t h e   " C o n f i r m "   b u t t o n ,   t h e   c o d e   u p d a t e s   t h e   d a t a b a s e   a n d   c h a n g e s   t h e   u s e r ' s   p a s s w o r d   e f f e c t i v e l y .  
  
 -   * * a d m i n i s t r a t i o n . p h p * *  
  
 T h i s   p a g e   a l l o w s   t h e   w e b s i t e ' s   a d m i n i s t r a t o r   t o   m a n a g e   t h e   u s e r s .   T h e   u s e r s   a r e   d i s p l a y e d   o n   t h e   p a g e   b u t   t h e   a d m i n i s t r a t o r   c a n   c h o o s e   t o   h i d e   o r   r e v e a l   t h e   l i s t .   H e   c a n   c h o o s e   t o   m o d i f y   a   u s e r ' s   p a s s w o r d ,   r o l e   a n d   e n a b l e / d i s a b l e   h i s   a c c o u n t .   H e   a l s o   c a n   a d d   a   u s e r   t o   t h e   d a t a b a s e   b y   p r o v i d i n g   a   u s e r n a m e   a n d   a   p a s s w o r d .  
  
 T h e   c o d e   i n   t h i s   p a g e   p e r f o r m s   a l l   t h e   S Q L i t e   r e q u e s t s   i n d u c e d   b y   t h e   a d m i n i s t r a t o r ' s   c h o i c e s .    
  
 -   * * l o g o u t . p h p * *  
  
 T h i s   p a g e   d e s t r o y s   t h e   u s e r ' s   s e s s i o n   a n d   t h e   s e s s i o n   c o o k i e .   A f t e r   l o g g i n g   o u t ,   t h e   u s e r   m u s t   l o g   i n   a g a i n   a n d   e n t e r   h i s   c r e d e n t i a l s   a g a i n .    
  
 -   * * f r a g m e n t s * *  
     -   * * h e a d e r . p h p * *  
  
     T h i s   p a g e   c o n n e c t s   t o   t h e   d a t a b a s e   a n d   e s t a b l i s h e s   t h e   u s e r ' s   r o l e   ( c o l l a b   /   a d m i n ) .   I f   t h e   u s e r   i s   a n   a d m i n i s t r a t o r ,   t h e   " A d m i n i s t r a t i o n "   b u t t o n   w i l l   b e   d i s p l a y e d   i n   t h e   h e a d e r   a n d   t h e r e f o r e ,   g i v e   t h i s   u s e r   a c c e s s   t o   t h e   l i n k e d   p a g e .     I t   a l s o   c h e c k s   i f   t h e   u s e r   i s   m a r k e d   a s   " a c t i v e "   ( " i n a c t i v e "   u s e r s   c a n n o t   l o g   i n ) .    
  
     -   * * f o o t e r . p h p * *  
  
     T h i s   p a g e   c o n t a i n s   t h e   n e c e s s a r y   c o d e   t o   d i s p l a y   t h e   t e m p l a t e   w e b s i t e   p a g e .  
  
     -   * * l e f t _ s i d e _ b a r . p h p * *  
  
     T h i s   p a g e   r e t r i e v e s   t h e   i n t e r e s t i n g   " C a t   F a c t s "   t h a t   a r e   i n c l u d e d   i n   t h i s   w e b s i t e ' s   t e m p l a t e .  
  
 -   * * f u n c t i o n s * *  
  
     -   * * c o n n e c t D B . p h p * *  
  
     T h i s   f u n c t i o n   e s t a b l i s h e s   a   n e w   c o n n e c t i o n   t o   t h e   d a t a b a s e   u s i n g   P D O .    
  
     -   * * m e s s a g e . p h p * *  
  
     T h i s   f u n c t i o n   g e t s   i n f o r m a t i o n s   a b o u t   t h e   m e s s a g e s   d i s p l a y e d   :   t h e   s e n d e r ,   t h e   r e c i p i e n t ,   t h e   d a t e   a n d   t i m e ,   t h e   s u b j e c t ,   t h e   c o n t e n t   a n d   t h e   v a r i o u s   I D s   ( b e c a u s e   o f   t h e   d a t a b a s e ) .   I t   c l e a n s   t h e   c o d e   b e c a u s e   w e   c a n   u s e   t h e   f u n c t i o n s   d e f i n e d   i n   t h i s   p a g e   i n s t e a d   o f   r e w r i t i n g   r e d u n d a n t   c o d e .  
  
     -   * * u t i l s . p h p * *  
  
     T h i s   f u n c t i o n   f a c i l i t a t e s   t h e   r e d i r e c t i o n s .   