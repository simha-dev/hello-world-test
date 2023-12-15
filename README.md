simha-preprod-push

s gsd dsg dsg
sdfsd fdsaf sdf sdf asdf dsa

readme change g dsgdg df

asdfgadsgvsadgv

sdfsdfdsfdsf
# About this action
sdfsadfasfasD

This is a test action. Do not use this in a workflow

- Edit readme

## Quickstart

    Choose Add to workflow to add the action code to the workflow.
    Choose Visual to open the visual editor.
    Complete the mandatory fields on the Inputs, Configuration, and Outputs tabs. For details on each field, see the Additional resources section below.
    Save, validate, and commit.
    Run the action.



## Workflow examples

The following example workflow shows the Hello World Test action in use.

Workflow 1: Simple workflow

Name: Hello_WorldWorkflow
SchemaVersion: 1.0
Triggers:
- Type: Push
  Branches:
    - main
Actions:
  HelloWorldAction:
    Identifier: aws/hello-world@v1
    Inputs:
      Sources:
        - WorkflowSource
    Configuration:
      Parameters:
        who-to-greet: Jack Sparrow!
