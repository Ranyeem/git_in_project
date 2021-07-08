/*
 * main.c
 *
 *  Created on: Jul 8, 2021
 *      Author: Raneem
 */
#include <avr/io.h>
#include <util/delay.h>
#define PORT_7_SEGMENT
#define DDRA_7_SEGMENT
#define num
#define E_NOK
#define count
void main()
{
	   // A7 A6 A5 .....A0
	DDRA_7_SEGMENT=0b11111111; //direction is o/p
	while(1)
	{
		if (num>10)
		return E_NOK;
	}
	else
		switch (count)
		{
			case 0:
				PORT_7_SEGMENT=0b01111111;
				break;
				_delay_ms(1000);
			case 1:
				PORT_7_SEGMENT=0b00110000;
				break;
				_delay_ms(1000);
			case 2:
				PORT_7_SEGMENT=0b01101101;
				break;
				_delay_ms(1000);
			case 3:
				PORT_7_SEGMENT=0b01111001;
				break;
		    	_delay_ms(1000);
			case 4:
				PORT_7_SEGMENT=0b00110011;
				break;
				_delay_ms(1000);
			case 5:
				PORT_7_SEGMENT=0b01011011;
				break;
			    _delay_ms(1000);
			case 6:
				PORT_7_SEGMENT=0b01011111;
				break;
				_delay_ms(1000)
			case 7:
				PORT_7_SEGMENT=0b01110000;
				break;
				_delay_ms(1000)
			case 8:
				PORT_7_SEGMENT=0b01111111;
				break;
				_delay_ms(1000)
			case 9:
				PORT_7_SEGMENT=0b01111011;
				break;
				_delay_ms(1000)
			{
					if (num==9)
		switch (count)
		case 8:
			PORT_7_SEGMENT=0b01111111;
			break;
			_delay_ms(1000)
	    case 7:
			PORT_7_SEGMENT=0b01110000;
			break;
			_delay_ms(1000)
		case 6:
			PORT_7_SEGMENT=0b01011111;
			break;
			_delay_ms(1000)
		case 5:
		    PORT_7_SEGMENT=0b01011011;
			break;
			_delay_ms(1000);
		case 4:
			PORT_7_SEGMENT=0b00110011;
			break;
			_delay_ms(1000);
		case 3:
			PORT_7_SEGMENT=0b01111001;
			break;
			_delay_ms(1000);
		case 2:
			PORT_7_SEGMENT=0b01101101;
			break;
			_delay_ms(1000);
		case 1:
			PORT_7_SEGMENT=0b00110000;
			break;
			_delay_ms(1000);
		case 0:
			PORT_7_SEGMENT=0b01111111;
			break;
			_delay_ms(1000);
			else
				return E_nok;
	}
}
