# timelapse

A quick-start multi-camera timelapse utility that uses streamer. Written in ruby. 

## Prerequisites

This script requires the installation of streamer:

	sudo apt-get install streamer

## Installation

	git clone git@github.com:dhulihan/observer.git
	cd observer

## Usage

* `timelapse-start` - Take a picture from all attached cameras/webcams at a set interval. The default interval is 0.001 fps (~ every 10 minutes). This will continue to run until interrupted.
* `timelapse-snap` - Take a single picture from every attached camera/webcam. This is good for testing your cameras or setting up a cron job.
