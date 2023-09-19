---
content_type: page
description: ''
draft: false
learning_resource_types:
- Readings
ocw_type: CourseSection
title: Readings
uid: 168b835a-d6fc-24a3-3113-0cc27e24ebbc
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
LEC #
{{< thclose >}}{{< thopen >}}
TOPICS
{{< thclose >}}{{< thopen >}}
READINGS
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen colspan="3" >}}
**Week 1**
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
1
{{< tdclose >}}{{< tdopen >}}
Dynamic Multithreading
{{< tdclose >}}{{< tdopen >}}

Cilk Manual 5.3.2 ({{% resource_link "76329e7e-d4b9-01ed-6e20-a11a17ae2ae3" "PDF" %}})

Minicourse on Multithreaded Programming ({{% resource_link "9cf3ee78-91b5-6e3e-9669-28ba8dced3f3" "PDF" %}}) (Courtesy of Harald Prokop. Used with permission.)

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen colspan="3" >}}
**Week 2**
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
3
{{< tdclose >}}{{< tdopen >}}
Serial Performance and Caching
{{< tdclose >}}{{< tdopen >}}

Sorting Code Handout ({{% resource_link "697ac643-4b96-c75a-9e35-f55799077796" "PDF" %}})

C Code for Sorting ({{% resource_link "b3deed7d-753c-d905-1ad9-652f9bfc0bae" "C" %}})

ASM Code for Sorting (Excerpt) ({{% resource_link "0832be1a-fdf7-c412-fff2-1d55e5d9a1c7" "ASM" %}})

*Cache-Oblivious Algorithms* 

Prokop's Masters Thesis ({{% resource_link "6dc7de52-dcf1-3b53-cebf-2fe10ae6752a" "PDF" %}})   
FOCS Paper ({{% resource_link "7e5331aa-e765-482e-8725-1ba75d9aeabe" "PDF" %}})

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen colspan="3" >}}
**Week 3**
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
4
{{< tdclose >}}{{< tdopen >}}
Determinacy Detection and Race Detection
{{< tdclose >}}{{< tdopen >}}

Feng, Mingdong, and Charles E. Leiserson. *Efficient Detection of Determinacy Races in Cilk Programs.*

Cheng, Guang-Ien, Mingdong Feng, Charles E. Leiserson, Keith H. Randall, and Andrew F. Stark. "Detecting Data Races in Cilk Programs that Use Locks." In *Proceedings of the Tenth Annual ACM Symposium on Parallel Algorithms and Architectures* (1998): 298-309.

The LCA Problem Revisited ({{% resource_link "e9bc5076-484a-9dd5-f731-15ef860ccc54" "PDF" %}}) (Courtesy of Martin Farach-Colton and Michael Bender. Used with permission.)

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
5
{{< tdclose >}}{{< tdopen >}}
Consistency of the Memory Sub-System
{{< tdclose >}}{{< tdopen >}}

Goodman, James R. *Using Cache Memory To Reduce Processor-Memory Traffic*. Department of Computer Sciences, University of Wisconsin-Madison Madison, WI: 19883, pp. 255-262.

Lamport, Leslie. "How to Make a Correct Multiprocess Program Execute Correctly on a Multiprocessor." *IEEE Trans. Computers* 46 (February 14, 1993).

Frigo, Matteo, and Victor Luchangco. "Computation-Centric Memory Models." To appear in *Proceedings of the Tenth Annual ACM Symposium on Parallel Algorithms And Architectures (SPAA).* MIT Laboratory for Computer Science, Massachusetts Institute of Technology. June 28-July 2, 1998.

Herlihy and Moss. *Transactional Memory: Architectural Support for Lock-Free Data Structures.* ({{% resource_link "edd23e96-38c4-675c-ffce-1341254837f1" "PDF" %}}) (Courtesy of Maurice Herlihy and J. Eliot Moss. Used with permission.)

Huang, Kai. *Data-Race Detection In Transaction Everywhere Parallel Programming.* ({{% resource_link "a160822f-d9fd-64d3-4058-72c26acdcea2" "PDF" %}})

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen colspan="3" >}}
**Week 4**
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
6
{{< tdclose >}}{{< tdopen >}}
Analyzing Space Bounds
{{< tdclose >}}{{< tdopen >}}

Blumofe, Robert D., Charles E. Leiserson. "Space-Efficient Scheduling of Multithreaded Computations." *SIAM Journal on Computing* 27, 1: 202-229. MIT Laboratory for Computer Science, Massachusetts.

Berger, Emery D., Kathryn S. McKinley, Robert D. Blumofe, and Paul R. Wilson. "Hoard: A Scalable Memory Allocator for Multithreaded Applications." In *Proceedings of the Ninth International Conference on Architectural Support for Programming Languages and Operating Systems*. Cambridge, MA: November 2000. Department of Computer Sciences, The University of Texas at Austin Austin, Texas. Department of Computer Science, University of Massachusetts Amherst, Massachusetts.

Blumofe, Robert D., Matteo Frigo, Christopher F. Joerg, Charles E. Leiserson, and Keith H. Randall. "An Analysis of Dag-Consistent Distributed Shared-Memory Algorithms." In *Proceedings of the 8th Annual ACM Symposium on Parallel Algorithms and* *Architectures (SPAA).* Department of Computer Sciences, The University of Texas at Austin, Texas. MIT Laboratory for Computer Science, Massachusetts.

Narlikar, Girija J., and Guy E. Blelloch. "Space-Efficient Scheduling of Nested Parallelism." *ACM Transactions on Programming Languages and Systems (TOPLAS)* 21, 1 (January 1999): 138-173. Carnegie Mellon University.

Vee and Hsu. A Scalable and Efficient Storage Allocator on Shared-Memory Multiprocessors. Singapore, Nanyang Avenue: Center for Advanced Information Systems, SAS Nanyang Technological University.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen colspan="3" >}}
**Week 5**
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
8
{{< tdclose >}}{{< tdopen >}}
Cilk Scheduler
{{< tdclose >}}{{< tdopen >}}
Executing Multithreaded Programs Efficiently
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen colspan="3" >}}
**Week 9**
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
14
{{< tdclose >}}{{< tdopen >}}
Competitive Snoopy Caching
{{< tdclose >}}{{< tdopen >}}

Karlin, Anna R., Mark S. Manasse, Larry Rudolph, and Daniel D. Sleator. "Competitive Snoopy Caching." *Algorithmica 3*. Springer-Verlag, New York Inc., 1988, pp. 79-119.

Karlin, Anna R., Mark S. Manasse, Lyle A. McGeochj, and Susan Owicki. "Competitive Randomized Algorithms for Non-Uniform Problems" In *Proceedings, Symposium on Discrete Algorithms.* 1990, chapter 33, pp. 301-309.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen colspan="3" >}}
**Week 13**
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
22
{{< tdclose >}}{{< tdopen >}}
Pick a Winner
{{< tdclose >}}{{< tdopen >}}
Awerbuch, Baruch, Yossi Azar, Amos Fiat, and Tom Leighton. "Making Commitments in the Face of Uncertainty: How to Pick a Winner Almost Every Time." In *Proceedings of the 28th Annual ACM Symposium on Theory of Computing* (1996): 519-530.
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}