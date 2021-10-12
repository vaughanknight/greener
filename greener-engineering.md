# Greener Engineering

The concept of green software is to create applications or software with the goal of emitting less carbon and to design for environmental sustainability. We can divide the concept into two categories: carbon efficient and carbon aware so that when we are designing for sustainability, we can look at our software and ask ourselves “Is our software/architecture carbon efficient?” or “Are we aware of the amount of carbon we are emitting and can we emit less?”. Here we address software as the problem and how we can be better at designing more green software.

# Carbon efficient

What can we do to make our software more carbon efficient? The key is to find areas in our application where we can be more energy and hardware efficient and then make the necessary changes in the software/architecture of an application so it is responsible for emitting less carbon. Depending on which changes you are able to make, you can see a reduction of emissions from 5 to 50%.

Some areas to consider:

- Algorithm efficiency
- Architectural efficiency
- Batch
- Caching
- Elasticity
- Low Priority VMs

## Energy efficient

Being energy efficient means to use less energy to do the same job. This means making sure that we optimize the processes we have running in our software which usually in turn increases performance of our applications so as a result, we are not only emitting less carbon but have an application that performs efficiently, which means less costs for our resources

## Hardware efficient

Using less hardware to do the same job applies to being more hardware efficient. You may have a server that sits in your data center but is barely used so rather than keeping it up and running 24/7 you can move it to the cloud and schedule the server to auto-shutdown after it is not used for a certain period of time. You can also try to run your workloads in data centers in different regions which may use more renewables and produce less carbon emissions (https://app.electricitymap.org/map). Depending on which changes you make, you can see a reduction of emissions from 5 to 97%.  

- High server utilization
- Efficient servers
- Renewable energy usage
- On-prem to the cloud
- Efficient data centers (such as leveraging underwater data centers or data centers that run on renewable energy)

# Carbon aware

Making our software carbon aware means changing the behavior of the application so it is responsible for emitting less carbon i.e. charge laptop when there are a lot of renewables. For example, for a gaming application like Xbox where the number of users doesn’t really change depending on the time of day, rather than running a nightly build at midnight, you can run the build early in the morning where you can leverage renewable resources (e.g. when the sun comes out) to run your builds.  

- Find opportunities in your application design where you can leverage more energy efficient resources (e.g. running build during daytime using renewable energy)
- Demand shaping – designing your application so that demand matches supply of carbon 
- Design to increase carbon usage awareness for the user (e.g. mobile showing how much carbon you used based on your daily app usage activity)


