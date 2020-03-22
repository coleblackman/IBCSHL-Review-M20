# Topic 6 Resource Management

## 6.1.1 Identify resources to be managed

- cache, primary memory, secondary storage, network bandwidth, processor speed, graphics processing





## 6.1.2 Evaluate resources available

> mainframe - the most powerful type of commercial computer; focus on processing a large amount of data and to be online constantly; lots of parallel processing power; used by large corporations; financial tracking, data management; uninterrupted operation; backwards compatibility; Reliability Availability Serviceability
  -   Transaction processing = information processing which is divided into many individual operations
>supercomputer - frontline of processing capacity; speed; FlOpS; 

## 6.1.3 Limitations of resources

- Many small computers have weak GPUs
- Single processor computers cannot render 3d graphics well

## 6.1.4 Issues with resource limitations

- Cache memory (if limited) - CPU waits for sluggish ram
- Storage device speed
- processor cores - slowdowns, limitations of number of active processes, mitigated by multithreading
- Bandwidth - computer waits to hear from network
- Display resolution
- Lack of GPU - CPU needs to do it
- Sound card

## 6.1.5 Role of OS

> Operating system (OS) - A set of programs through which a computer manages its own resources.
> Program - a nonactive set of instructions stored on disk. It may or may not become a job.
> Multitasking - execution of more than one program in memory (switching rapidly)
> Time sharing - resources shared between jobs, managed by OS
> Scheduling - determines which process should use resources
> Memory management

> Multitasking - tasks sharing a common resource

> Multiprocessing - more than one CPU being used at once

> Multiprogramming - more than one program at a time in memory, they are executed concurrently (switching rapidly)
> Paging - memory divided into equal sections (frames); programs divided into pages; a program does not have to be contiguous in memory; This way it can swap between ram and disk quickly so more programs can be concurrent

### Scheduling policies

- Round robin - running processes get a share of CPU time
- Prioritization - some processes are more important
- FiFo - as soon as a process is ready it gets CPU time

## Software/Hardware interrupts

- Signal that stops the CPU and forces it to do something else immediately

Interrupts vs polling

| Interrupts                                             | Polling                    |
|--------------------------------------------------------|----------------------------|
| CPU time saved because it doesnt have to keep checking | Too many interrupts is bad |
| Less control over CPU                                  | more control               |

