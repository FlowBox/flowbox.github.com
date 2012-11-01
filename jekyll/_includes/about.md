The processing of voluminous flow measurement data such as NetFlow is a challenging task since it requires to process millions of flows within limited time to deliver statistics, reports, or on-line alerts to the user.

Therefore we developed FlowBox, a toolbox for on-line flow processing that addresses the needs of network operators and researchers. The core of FlowBox is designed to allow for multiple processors and parallel processing to speed up data mining. To reduce the time required to build a new analysis or alerting system, FlowBox is organized in loosely coupled modules that can easily be reused or extended to implement the required functionality within short time. Additionally, FlowBox provides an interface written in Ruby, which allows users to quickly evaluate new ideas in a comfortable way.

Further, thanks to the Ruby interface, any data processing chain can be easily integrated into a Ruby on Rails (RoR) project. This web framework is well known for its ease of use and its nice rapid prototyping properties. All standard FlowBox processing units are already integrated into a stub RoR project that can be used to configure, control, and monitor the data processing. By extending this existing project you can implement your customized a high-level user interface within a short time.

Interested in FlowBox? Then just contact us! Any help in the project is highly appreciated!

We are currently working on the first public release that should be published soon under [https://github.com/FlowBox](https://github.com/FlowBox)
