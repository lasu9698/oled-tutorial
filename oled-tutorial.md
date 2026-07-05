# OLED Screen
Let's write a program to show the word "hello" on the OLED Screen

```package
environment = github:tinkertanker/pxt-iot-environment-kit

```

## Step 1
First, we need to set up the OLED screen by adding the OLED ``||OLED: initialize OLED with width 128 and height 64||`` block inside the basic ``||basic: on start||`` block


```blocks
OLED.init(128, 64)
```


## Step 2
Go to OLED ``||OLED : show string||``  and put it inside basic ``||basic: on start||`` block under where you initialize the screen


This step is to setup the command to show the text on your OLED screen

```blocks
OLED.init(128, 64)
OLED.writeStringNewLine("")

```

## Step 3
Inside the quotation in OLED  ``||OLED : show string||`` block, type a word/sentence you want to display on the screen. For example, type "hello"
```blocks
OLED.init(128, 64)
OLED.writeStringNewLine("hello")

```