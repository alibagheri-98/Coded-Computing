# Coded-Computing
I make
# Abstract
The abstract introduces "coded computing," a novel approach that employs coding theory to enhance large-scale distributed computing. It addresses communication, straggler delays, privacy, and security issues. Key contributions include:

1. **Coded Distributed Computing (CDC):** Reduces communication load in MapReduce-based systems, achieving optimal computation-communication balance.

2. **Straggler Mitigation:** Introduces "Polynomial Codes" and "Lagrange Coded Computing" to minimize computation latency by distributing redundant data/computation across nodes.

3. **Security and Privacy:** Extends LCC for robust security and privacy with minimal coding overhead.

4. **Real-World Impact:** Implements coded computing in cloud-based systems, significantly improving performance in tasks like sorting and regression model training.

In short, coded computing optimizes distributed computing by leveraging coding theory to address various challenges effectively.

# Introduction
This monograph addresses the challenges faced by large-scale machine learning and big data analytics in the context of cloud infrastructures. These applications rely on distributed computing across datacenters, where data is spread across numerous low-end servers. To tackle major performance bottlenecks, the authors propose "coded computing," a novel approach inspired by coding theory. This approach optimally introduces redundancy in distributed systems to overcome communication, straggler, and security issues.

Key points:

1. **Background:** The rapid growth of data-intensive applications like voice/image recognition and real-time mapping relies on distributed computing within cloud infrastructures.

2. **Bottlenecks:** The three primary performance bottlenecks are communication, stragglers (slow or failing nodes), and security vulnerabilities.

3. **Coded Computing:** The authors propose "coded computing" as a unique solution, leveraging coding theory to address these bottlenecks by introducing and utilizing redundancy strategically.

4. **Applications:** Coded computing is applied to various distributed computing frameworks, from general MapReduce tasks to polynomial algebra, and across different computing systems, including cloud-based datacenters and emerging edge/fog computing systems.

5. **Cost Considerations:** Coded computing involves redundantly storing datasets, incurring communication and storage costs. However, these costs can often be amortized over multiple computations, and dataset encoding and storage can occur during off-peak network times.

In summary, this monograph explores the use of coded computing to optimize large-scale distributed machine learning and data analytics systems, offering solutions for communication, straggler, and security challenges within cloud infrastructures.
