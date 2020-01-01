# imgui-java
A handcrafted 1-1 Java binding for [Dear-ImGui](https://github.com/ocornut/imgui).

*Some of the very specific features are still in a wip state.*

## How to use
TBA

##### Binding notice:
* Since it's a 1-1 binding please consider to see official [documentation](https://github.com/ocornut/imgui#usage) and [wiki](https://github.com/ocornut/imgui/wiki) 
  to get more info about how to do things.
* In places where in C++ you need to pass `ImVec2` or `ImVec4`, you'll need to pass two or four float parameters respectively.
* When you need to get an output from the Dear-ImGui use wrappers for primitives: `ImBool`, `ImInt` etc.
* Due to the Java and JNI restrictions we can't provide a fully fledged callbacks to the ImGui::InputText*() methods.
  Partly you could replace some of the features (like providing of the allowed chars to input) by using the ImGuiInputTextData class. Read javadoc to get more info.

## How to build
TBA

## Credits
This binding is based on the work of [xpenatan](https://github.com/xpenatan) and his version of the binding [jDear-imgui](https://github.com/xpenatan/jDear-imgui).

## License
See the LICENSE file for license rights and limitations (Apache-2.0).