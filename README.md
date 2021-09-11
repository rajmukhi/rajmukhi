ble>
                        <tr>
                            
                            <td>
                                <div class="container" id="quiz">
                                    <img src="quizimage.jpg" alt="quiz" class="image" width="250px" height="250px">
                                <div class="overlay" id="quiz">
                                <a href="quiz.php"><div class="text" id="quiz">Go to Quiz</div></a>
                                    </div>
                                </div>
                            </td>
                            
                            <td>
                                <div class="container1" id="store">
                                    <img src=storeimage.jpg alt="store" class="image1" width="250px" height="250px">
                                <div class="overlay1" id="store">
                                    <a href="products.php"><div class="text1" id="store">Proceed to Store</div></a></div>
                                </div>
                            </td>
                            
                            <td>
                                <div class="container2" id="legends">
                                    <img src="legends.jpg" alt="legends" class="image2" width="250px" height="250px">
                                <div class="overlay2" id="legends">
                                    <a href="legends.php"><div class="text2" id="legends">Legends</div></a></div>
                                </div>
                            </td>
                            
                        </tr>
                </table>


#quiz.container:hover .overlay {
                    width: 100%;
                    }

    #quiz.overlay {
                position: absolute;
                bottom: 0;
                left: 0;
                right: 0;
                background-color: #11d11f;
                overflow: hidden;
                width: 0;
                height: 100%;
                transition: .5s ease;
                }

    
    #quiz.text {
                white-space: nowrap; 
                color: white;
                font-size: 20px;
                position: absolute;
                overflow: hidden;
                top: 50%;
                left: 50%;
                transform: translate(-50%, -50%);
                -ms-transform: translate(-50%, -50%);
                }




    #store.container1 {
                position: relative;
                width: 100%;
                left:280px;
                }



    #store.overlay1 {
                position: absolute;
                bottom: 100%;
                left: 0;
                right: 0;
                background-color: #11d11f;
                overflow: hidden;
                width: 100%;
                height:0;
                transition: .5s ease;
                }

    #store.container1:hover .overlay1 {
                bottom: 0;
                height: 100%;
                }

    #store.text1 {
                white-space: nowrap; 
                color: white;
                font-size: 20px;
                position: absolute;
                overflow: hidden;
                top: 50%;
                left: 50%;
                transform: translate(-50%, -50%);
                -ms-transform: translate(-50%, -50%);
                }



    #legends.container2 {
                position: relative;
                width: 100%;
                left: 450px;
                }


    #legends.overlay2 {
                position: absolute;
                bottom: 0;
                left: 100%;
                right: 0;
                background-color: #11d11f;
                overflow: hidden;
                width: 0;
                height: 100%;
                transition: .5s ease;
                }

    #legends.container2:hover .overlay2 {
                width: 100%;
                left: 0;
                }

    #legends.text2 {
                white-space: nowrap; 
                color: white;
                font-size: 20px;
                position: absolute;
                overflow: hidden;
                top: 50%;
                left: 50%;
                transform: translate(-50%, -50%);
                -ms-transform: translate(-50%, -50%);
                }
