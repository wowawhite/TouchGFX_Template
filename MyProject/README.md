STM32 CubeIDE 1.3.0 and TouchGFX 4.13.0 Template on STM32F746G-DISCO
=================

This is a Template for an STM32F746 Disco Board which uses the TouchGFX framework to implement
a simple switch button on the onboard LCD.
This template was created with the linux version of CubeIDE. 

To launch debug you have to change the file "MyProject.launch" the following lines:
<stringAttribute key="com.st.stm32cube.ide.mcu.debug.launch.loadList" value="... Debug/MyProject.elf&quot; ..."
<stringAttribute key="com.st.stm32cube.ide.mcu.debug.stlink.log_file" value="/home/"your user name"/STM32CubeIDE/workspace_stm/MyProject/Debug/st-link_gdbserver_log.txt"/>
to your paths.

The template was produced following this tutorial:
https://www.youtube.com/watch?v=12KXreXaLp0
Thanks to EE by Karl.

Feel free to use for your projects.