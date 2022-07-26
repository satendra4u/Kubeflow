# Kubeflow
A Kubeflow pipeline is a portable and scalable definition of a machine learning (ML) workflow. Each step in your ML workflow, 
such as preparing data or training a model, is an instance of a pipeline component. This document provides an overview of pipeline concepts and 
best practices, and instructions describing how to build an ML pipeline.


<b>Understanding pipelines</b>

A Kubeflow pipeline is a portable and scalable definition of an ML workflow, based on containers. A pipeline is composed of a set of input parameters and 
a list of the steps in this workflow. Each step in a pipeline is an instance of a component, which is represented as an instance of ContainerOp.

<b>You can use pipelines to:</b>

<li>Orchestrate repeatable ML workflows.</li>
<li>Accelerate experimentation by running a workflow with different sets of hyperparameters.</li>
<li>Understanding pipeline components</li>
<li>A pipeline component is a containerized application that performs one step in a pipeline's workflow. Pipeline components are defined in 
component specifications, which define the following:</li>

</p>
</p>
</p>


<b>Understanding the pipeline graph</b>

Each step in your pipeline's workflow is an instance of a component. When you define your pipeline, you specify the source of each step's inputs. 
Step inputs can be set from the pipeline's input arguments, constants, or step inputs can depend on the outputs of other steps in this pipeline. Kubeflow Pipelines uses these dependencies to define your pipeline's workflow as a graph.

<b>Sample Kubeflow</b>

This example is a demonstration of sample kubeflow to build and deploy on kubeflow cluster and check the execution graph for its output. 
