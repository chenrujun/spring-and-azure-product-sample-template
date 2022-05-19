
# Background

This is a template repository for Spring on Azure sample repositories. All repositories created by current template should be listed in [spring-and-azure-product-samples](https://github.com/chenrujun/spring-and-azure-product-samples). The template is still work in process.


# Requirement of this template
1. README should follow the same pattern, for example:
```
# Introduction
This repository is used to ...

# Repository Information
spring-boot version: 2.6.7
spring-and-azure-product-sample-template version: 1.0.0

# Learnning Path
Assume each repository have more than one sample, for example: sample-1, sample-2, sample-3, sample-4. Learnning path should be provided.
Here is an example of learning path:

sample-1  -->  sample-2  -->  sample-4
sample-3  ----------------------↑

Which means:
1. If you want lean sample-2, you must learn sample-1 first. 
2. If you want to learn sample-3, you do NOT need to learn sample-1 and sample-2 first.
3. If you want to learn sample-4, you must learn sample-2 and sample-3 first

# Run This Sample  (This may appear in sample-x/README.md)

## Pre-requisites

1. Java. Version >= 8
2. Maven. Version >= 3.8  (Not use gradle, because maven can cover more customers)
3. Azure Subscription

## Create Azure resource
You can choose one of the following ways to create Azure resource:
1. Azure Protal
2. Azure CLI (Link to another markdown file)
3. Azure PowerShell (Link to another markdown file)
4. Terraform (Link to another markdown file)

## etc.. TO BE DONE

```


2. Make external dependency updated. For example [dependabot.yml](https://docs.github.com/en/code-security/dependabot/dependabot-version-updates/configuration-options-for-the-dependabot.yml-file) can be used.

3. Support multiple spring-boot version. For example: Use different branch (`spring-boot_2.5` and `spring-boot_2.6`) to support different spring-boot versions.

4. The template repository can do release, after the template repository released a new version, all samples should update to latest release version. Manually, ofcourse.

5. Use [GitHub Template Repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository) to manage this reposiroty, so we can use the extra features about template reposiroty.

6. etc.. TO BE DONE
