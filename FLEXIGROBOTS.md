# Introduction

Purpose of this module fork is to have RTMP server extract and send latest frame from input stream as JPEG to 
AI servive that does object detection for the image stream

# Notes

Likely point to inject frame extraction and sending at line 872 at [ngx_rtmp_record_module](ngx_rtmp_record_module.c)
at function "ngx_rtmp_record_write_frame"
