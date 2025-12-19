# Neon Stop Clock

Neon Stop Clock is a browser-based count-up / multi-interval countdown timer with configurable visual and audible alarms.

It is designed for situations where time discipline matters — for example meetings, presentations, workshops, or timed exercises — allowing presenters or facilitators to stay on schedule without constant manual monitoring.

The timer supports up to six sequential intervals. In countdown mode, the clock triggers a visual and/or audible alarm at the end of each interval, making it suitable for structured sessions with predefined time blocks.

## Features

- Count up or countdown modes
- Up to 6 configurable intervals
- Visual alarm (neon flash effect)
- Audible alarm (Web Audio API)
- Adjustable colour, size, and volume
- Fully client-side (no dependencies)

## Demo

https://johnfullerroot.github.io/neon-stop-clock/

## Usage

### Select mode
- Enable **Count Up** to use the clock as a stopwatch.
- Enable **Count Down** to configure one or more timed intervals.

### Configure intervals (Count Down mode)
- Set the duration for **Interval 1** using the hours, minutes, and seconds inputs.
- Click **“+”** to add up to five additional intervals.
- Each enabled interval is added sequentially to the total countdown time.

### Configure alarms
- Enable **Visual Alarm** for a flashing on-screen alert.
- Enable **Audible Alarm** for a repeating tone.
- At least one alarm must be enabled when countdown intervals are set.

### Customise display
- Adjust **Colour** to change the neon hue.
- Adjust **Size** to scale the timer display.
- Adjust **Volume** when audible alarms are enabled.

### Control the timer
- Click **Start** to begin timing.
- Click **Stop** to pause.
- Click **Reset** to clear all intervals and return to the initial state.

## License

GPL-3.0-only
