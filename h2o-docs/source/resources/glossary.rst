.. -*- mode: rst -*-

.. _glossary:


Glossary
========

.. glossary::

**binomial**
  A variable that takes on only the value 0 or 1. Binomial variables
  are often interpreted as 0, which indicates that an event hasn't occurred
  or that the observation lacks a feature, where 1 indicates occurrence
  or display of an attribute.  

**categorical data or categorical variable**
  A qualitative variable (for example: blood type); synonym for
  enumerator, factor.  

**cloud**
  (Synonym for cluster.)  See the definition of cluster. 

**cluster**
  1. (Synonym for cloud.)  A group of H2O nodes that work together; when a
  job is submitted to a cluster, all the nodes in the cluster work on
  a portion of the job. 

  2. In statistics, a cluster is a  group of
  observations from a data set that have been identified as 
  similar according to a particular clustering algorithm.

**continuous** 
  A variable that can take on all or nearly all values along an
  interval on the real number line. 


**CSV file**
  CSV is an acronym for comma-separated value. A CSV file stores
  data in a plain text format. 

**destination key**   
  Automatically-generated key for a model; it allows recall of a
  specific model later in analysis. Users can specify a
  different destination key than the key generated by H2O. 

**deviance** 
  Deviance is the difference between an expected value and an observed value. 
  It plays a critical role in defining GLM models. For a more detailed
  discussion of deviance please see the H2O Data Science documentation
  on GLM. 

**DKV**
  Distributed key/value store; see key/value store.

**family**
  In GLM, family describes the options available for predictive
  modeling in GLM. Also see gaussian, poisson, gamma, binomial.
   
**feature**
  Synonym for attribute, predictor, or independent variable. Usually
  the data observed on features are given in the columns of a data
  set.  

**gz (gzipped) file**
  Gzip is a type of file compression, a gzipped file is a file
  compressed by gzip.   
  
**h2o.ai**
  Makers of H2O. Visit our `website:<www.h2o.ai>`.   

**HEX format**
  Records made up of hexadecimal numbers that represent machine
  language code or constant data. In H2O, data must be parsed into 
  .hex format before you can perform operations on it.   

**instance**
  H2O creates an instance each time you run H2O. During the initialization process, H2O    builds a cluster of nodes, depending on your configuration. If you are running a local instance on your laptop, H2O builds a one-node cluster. If you are running H2O on a series of machines, H2O builds a cluster using all available resources. The instance begins when the cluster is formed, and terminates when the program is closed and the cloud is terminated.

**job**
  A piece of work that needs to be done. For example, reading a file, parsing data, or building a model. In the browser-based GUI of H2O, each job is listed in the **Admin** menu under **Jobs**.   

**key**
  The .hex key generated when data are parsed into
  H2O. In the web-based GUI, a "key" is an input on each page where users
  define models, and also any page where users validate models on a
  new data set or use a model to generate predictions.    

**key/value pair**
  A type of data that associates a particular key index to a
  certain datum.  

**key/value store**
  A tool that allows storage of schema-less data. Data usually
  consists of a string, which represents the key, and the data itself,
  which is the value.

**L1 regularization** 
  A regularization method that constrains the absolute value of the weights and
  has the net effect of dropping some weights (setting them to zero) from a model
  to reduce complexity and avoid overfitting. 

**L2 Regularization** 
  A regularization method that constrains the sum of the squared
  weights. This method introduces bias into parameter estimates, but
  frequently produces substantial gains in modeling as estimate variance is
  reduced.

**link function** 
  A user-defined option in GLM. Refer to :ref:`GLMmath` for more information.  

**loss function**
  Synonymous to objective function and criterion function; the loss function is the     function minimized in order to achieve a desired estimator. For example, linear regression defines the set of best parameter estimates as the set of estimates that produce the minimum of the sum of the squared errors. Errors are the difference between the predicted value and the observed value for an observation.  

**n-folds** 
  User-defined number of cross-validation models generated by H2O.

**node**
  In distributed computing systems, nodes include clients,
  servers or peers. 
  
  In statistics, a node is a decision or terminal point in a
  classification tree.

**parse**
  Analysis of a string of symbols or datum that converts a set of information from a person-readable format to a machine-readable format.


**seed**
  A starting point for randomization. Seed specification is used when
  machine learning models have a random component; it allows users to
  recreate the exact "random" conditions used in a model at a later
  time. 

**standard deviation**
  Abbreviated **sd**.
  The standard deviation of the data in the column, defined as the
  square root of the sum of the deviance of observed values from the
  mean, divided by the number of elements in the column less one.
   

**standardization**
  Transformation of a variable so that it is mean-centered at 0 and
  scaled by the standard deviation.

**XLS file**
  A Microsoft Excel 2003-2007 spreadsheet file format. 

**Y**
  Dependent variable used in GLM; a user defined input selected
  from the set of variables present in the user's data. 
