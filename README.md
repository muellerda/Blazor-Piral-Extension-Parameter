# Blazor-Piral-Extension-Parameter



There are two extensions in total:

ParentExtension
ChildExtension

ParentExtension renders ChildExtension

Page "testpage" renders "ParentExtension".

Expectation: ParentExtension renders ChildExtension and displays text "Working!...".

Behavior:
The ChildExtension is rendered twice.

In my view, this behavior is not correct.