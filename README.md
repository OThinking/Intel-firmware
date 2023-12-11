# Intel-firmware
## STM32(interupt)
```
while (1)
  {
    /* USER CODE END WHILE */

    /* USER CODE BEGIN 3 */
    //int r = HAL_GPIO_ReadPin(B1_GPIO_Port, B1_Pin);
    //if(i != val){
    if(val == 1){
      //for(int i=0;i<val;i++){ // button pushed 0
      HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 0);

    }
    else if(val == 0){
      HAL_GPIO_TogglePin(LD2_GPIO_Port, LD2_Pin);
//      HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 1); // LED On / 1 = HIGH
        HAL_Delay(200); // delay 1 second
        //HAL_Delay(200);
        //flag = 0;
      //}
     }
  }
```
### Intel-firmware
#### Intel-firmware
