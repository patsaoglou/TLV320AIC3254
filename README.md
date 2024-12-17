## Basic firmware for the TLV320AIC3254 codec:

- Connecting left and right IN1-L IN1-R to left and right adc
- Powering up analog blocks, adc's and dac.
- Connecting left and right dac with LOL LOR
- Sampling Frequency: 48.000khz Data size: 16Bit Extended Note: Check in main.c file the function void tlv320_Init(I2C_HandleTypeDef *hi2c2).
