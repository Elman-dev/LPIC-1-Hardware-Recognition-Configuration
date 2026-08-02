# LPIC-1 | Hardware Recognition & Configuration

> Notes and summary of the first LPIC-1 lesson about Linux hardware architecture and hardware interaction.

---

## موضوعات اصلی این مطلب

### Hardware, Firmware & Operating System

هر سیستم کامپیوتری از سه لایه تشکیل شده:

- Hardware
- Firmware
- Operating System

سیستم‌عامل با استفاده از Firmware سخت‌افزار را مدیریت میکنه.

---

## BIOS vs UEFI

### BIOS

- نسل قدیمی Firmware
- فرآیند بوت کلاسیک
- محدودیت در اندازه دیسک

### UEFI

- بوت سریع‌تر
- امنیت بیشتر
- پشتیبانی از GPT
- قابلیت‌های توسعه‌یافته

---

## Peripheral Devices

نمونه دستگاه‌های جانبی:

- Network Card
- Graphics Card
- Audio Card
- Bluetooth Adapter
- External HDD
- Keyboard

---

## PCI Express

رابط استاندارد اتصال کارت‌های توسعه مانند:

- GPU
- Network Card
- NVMe SSD
- Audio Card

---

## USB

انواع مهمش:

- USB Type A
- USB Type B
- Mini USB
- Micro USB
- USB Type C

---

## GPIO

پایه‌های ورودی/خروجی قابل برنامه‌ریزی برای ارتباط با سخت‌افزارهای خارجی.

---

## Linux Hardware Interfaces

### /sys

نمایش اطلاعات سخت‌افزار و زیرسیستم‌های کرنل.

### /dev

نمایش دستگاه‌ها به صورت فایل.

مثال:

/dev/sda
/dev/tty

### udev

مدیریت خودکار فایل‌های دستگاه هنگام اتصال یا جداسازی سخت‌افزار.

### D-Bus

سیستم IPC برای ارتباط بین برنامه‌ها و سرویس‌های لینوکس.

### /proc

نمایش اطلاعات کرنل و پردازه‌ها.

فایل‌های مهمش:

- cpuinfo
- meminfo
- interrupts
- net

امیدوارم این مطلب براتون مفید بوده باشه

## Topics Covered

### Hardware, Firmware & Operating System

A computer system consists of three major layers:

- Hardware
- Firmware
- Operating System

The operating system communicates with hardware through the firmware.

---

## BIOS vs UEFI

### BIOS

- Legacy firmware
- Traditional boot process
- Limited disk support

### UEFI

- Faster boot
- Better security
- GPT support
- Modern firmware architecture

---

## Peripheral Devices

Examples include:

- Network Card
- Graphics Card
- Audio Card
- Bluetooth Adapter
- External HDD
- Keyboard

---

## PCI Express

PCIe is the standard expansion interface used for:

- GPUs
- Network Cards
- NVMe SSDs
- Audio Cards

---

## USB

Common connector types:

- USB Type-A
- USB Type-B
- Mini USB
- Micro USB
- USB Type-C

---

## GPIO

Programmable input/output pins used in embedded systems such as Raspberry Pi.

---

## Linux Hardware Interfaces

### /sys

Kernel hardware information.

### /dev

Device files.

Example:

/dev/sda
/dev/tty

### udev

Automatically creates and removes device files.

### D-Bus

IPC mechanism for communication between Linux services and applications.

### /proc

Virtual filesystem containing kernel and process information.

Important files:

- cpuinfo
- meminfo
- interrupts
- net

---

I hope you found this helpful and enjoyed the experience!
