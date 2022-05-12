#!/bin/bash

source ./config.cfg

nmcli dev set $DEVICE managed no
nmcli dev status
ifconfig $DEVICE down
iwconfig $DEVICE mode monitor
rfkill unblock all
ifconfig $DEVICE up
airmon-ng start $DEVICE
