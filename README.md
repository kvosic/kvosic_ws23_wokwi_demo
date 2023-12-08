![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/wokwi_test/badge.svg)

Demo project implemented in **Wokwi** for KV Integrated Circuit Design, WS 2023. (c) Harald Pretl, IIC@JKU.

## Description

A simple 4b binary asynchronous counter is realized in Verilog. On asserting reset (asynchronous), it is set to 0, and on a positive clock edge it is counting up.

The counter value is output using `uo_out[3:0]`.
