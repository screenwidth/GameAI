$NNGA
========

A neural networks combine genetic algorithm module.


Look how easy it is to use:
------------------------------

    import neuralNetworkGA

    # Init algorithm
    
    ai = NeuroGA(4,[30],1) 
    
    # Get networks
    
    gen = ai.next_gen_networks() 
    
    # Input values then calculate with neural network, return result.
    
    res = gen[i].put_inputs(inputs)
    
    # Use score to mark a network to value this network bad or good.
    
    ai.mark_score(score,gen[i])
    
    # Save result
    
    savenet(gen[i],1)
    
    # Load result
    
    geni = loadnet('gen_1')
    
    res = geni.put_inputs(observation) ...

You can see demos through download files.(Source file)

We provide several demos to show how to use these module in games.

And you can also see source code and demos on github.


Features
--------

- You do not need to know the algorithm.
- Make things faster
- Use the GA to train games of yourself.


Installation
------------

Install NNGA by running:

    pip install NNGA

 
Contribute
----------

- Source Code: 

Support
-------

If you are having issues, please let us know.

We have a mailing list located at: 3075489925@qq.com