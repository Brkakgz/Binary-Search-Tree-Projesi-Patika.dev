# Binary-Search-Tree-Projesi-Patika.dev
Binary Search Tree Projesi

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Birinci değerimiz root olarak ele alalım. 7 değerimiz artık bizim root değerimizdir.

                                              7
																							
İkinci olarak 5 değeri 7 değerinden küçük olduğundan 7'nin soluna yazılır.

                                              7
                                            /
                                          5 
																					
Üçüncü olarak 1 değeri 7 değerinden küçük olduğundan sol tarafa 5 değerinden de küçük olduğundan 5'in soluna yazılır.

                                              7
                                            /
                                          5 
                                         /
                                       1
																			 
Dördüncü olarak 8 değeri 7 değerinden büyük olduğundan 7'nin sağına yazılır.

                                              7
                                            /   \
                                          5       8
                                         /
                                       1
																			 
Beşinci olarak 3 değeri 7 ve 5 değerlerinden küçük olduğundan 1 değerine geliriz. 1 değerinden büyük olduğundan 1'in sağına yazarız.

                                              7
                                            /   \
                                          5       8
                                         /
                                       1
                                        \
                                          3
																					
Altıncı olarak 6 değeri 7'den küçük olduğundan soldan devam ederiz ve 5'e ulaşırız. 5 değerinden büyük olduğundan 5'in sağına yazarız.

                                              7
                                            /   \
                                          5       8
                                         /  \
                                       1     6
                                        \
                                          3
																					
Yedinci aşamada 0 değeri 7 5 ve 1 değerlerinden küçük olduğundan 1 değerinin soluna yazarız.

                                              7
                                            /   \
                                          5       8
                                         /  \
                                       1     6
                                     /   \
                                   0       3
																	 
Sekizinci aşamada 9 değeri 7 ve 8 değerinden büyük olduğu için 8 değerinin sağına yazarız.

                                              7
                                            /   \
                                          5       8
                                         /  \        \
                                       1     6         9
                                     /   \
                                   0       3
																	 
Dokuzuncu aşamada 4 değeri 7 ve 5 değerlerinden küçük, 1 ve 3 değerlerinden büyüktür bu yüzden 3 değerinin sağına yazılır.

                                              7
                                            /   \
                                          5       8
                                         /  \        \
                                       1     6         9
                                     /   \
                                   0       3
                                             \
                                               4
																							 
Onuncu aşamada 2 değeri 7 ve 5 değerlerinden küçük 1 değerinden büyük olduğundan 3 değerine ulaşırız. 3 değerinden küçük olduğu için 3 değerinin soluna yazarız. 

                                              7
                                            /   \
                                          5       8
                                         /  \        \
                                       1     6         9
                                     /   \
                                   0       3
                                         /    \
                                        2       4
																				
