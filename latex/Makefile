chapters1 = intro/intro.tex logic/logic.tex numbers/numbers.tex information/information.tex control/control.tex
chapters2 = arduinoStart/arduinoStart.tex buttonSerial/buttonSerial.tex communications/communications.tex 
chapters3 = dataCollection/dataCollection.tex dataTransfer/dataTransfer.tex dcMotors/dcMotors.tex displays/displays.tex
chapters4 = inertialMeasurements/imu.tex otherEnvironments/otherEnvironments.tex sampling/sampling.tex pwm/pwm.tex

manual.pdf : manual.tex $(chapters1) $(chapters2) $(chapters3) $(chapters4)
	latexmk -pdf manual
	mv manual.pdf ../docs/Fundamentals-of-Microcontrollers.pdf

clean:
	rm *.pdf
	find .. -type f -name '*.aux' -delete
	rm ../docs/*.pdf
