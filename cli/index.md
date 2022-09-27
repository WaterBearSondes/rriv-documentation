# Command Line Interface

## Overview

## Commands

NAME
### set-interval <sampling-interval-time-in-minutes>

SYNOPSIS<br/>
Variable entered after command is the sampling interval time in minutes.

DESCRIPTION<br/>
Sets the number of minutes between sampling events. Specifically sets the interval for the wake-up time.


NAME
### set-slot-config {"slot":4,"type":"generic_analog","tag":"two","burst_size":10}

SYNOPSIS<br/>
Places a particular sensor in a given slot.

DESCRIPTION<br/>
Sets the number of minutes between sampling events. Specifically sets the interval for the wake-up time.

### set-start-up-delay {time-in-minutes}
NAME

SYNOPSIS<br/>
Variable entered after command is the start-up delay time in minutes.

DESCRIPTION<br/>
Sets the number of minutes before the device will begin logging after wake.

### set-rtc

NAME<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
set-rtc - set real time clock epoch time<br/><br/>

SYNOPSIS<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
set-rtc<br/><br/>

DESCRIPTION<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Sets the real time clock on a connected RRIV device to unix epoch time as reported by the attached computer.<br/>
<br/>

### get-rtc

NAME<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
get-rtc - get the current real time clock epoch time stored on a RRIV device<br/><br/>

SYNOPSIS<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
get-rtc<br/><br/>

DESCRIPTION<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Retrieves the epoch time from the real time clock chip (DS3231) on a RRIV device.
<br/>
