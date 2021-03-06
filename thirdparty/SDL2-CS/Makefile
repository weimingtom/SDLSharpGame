# Makefile for SDL2#
# Written by Ethan "flibitijibibo" Lee

# Dependencies
DEPS = \
	-r:System \
	-r:System.Drawing \
	-r:System.Xml

# Source Lists
SDL2 = \
	src/LPUtf8StrMarshaler.cs \
	src/SDL2.cs \
	src/SDL2_image.cs \
	src/SDL2_mixer.cs \
	src/SDL2_ttf.cs
MINITK = \
	src/MiniTK/BlittableValueType.cs \
	src/MiniTK/Math/Quaterniond.cs \
	src/MiniTK/Math/Vector4.cs \
	src/MiniTK/Math/Vector3h.cs \
	src/MiniTK/Math/Vector2.cs \
	src/MiniTK/Math/Vector4h.cs \
	src/MiniTK/Math/Functions.cs \
	src/MiniTK/Math/BezierCurve.cs \
	src/MiniTK/Math/Rectangle.cs \
	src/MiniTK/Math/Quaternion.cs \
	src/MiniTK/Math/Size.cs \
	src/MiniTK/Math/Vector4d.cs \
	src/MiniTK/Math/Point.cs \
	src/MiniTK/Math/MathHelper.cs \
	src/MiniTK/Math/Matrix4.cs \
	src/MiniTK/Math/Box2.cs \
	src/MiniTK/Math/Half.cs \
	src/MiniTK/Math/Matrix4d.cs \
	src/MiniTK/Math/Vector3d.cs \
	src/MiniTK/Math/Vector2d.cs \
	src/MiniTK/Math/BezierCurveQuadric.cs \
	src/MiniTK/Math/Matrix3d.cs \
	src/MiniTK/Math/Vector2h.cs \
	src/MiniTK/Math/BezierCurveCubic.cs \
	src/MiniTK/Math/Vector3.cs \
	src/MiniTK/AutoGeneratedAttribute.cs \
	src/MiniTK/ContextHandle.cs \
	src/MiniTK/Graphics/GraphicsBindingsBase.cs \
	src/MiniTK/Graphics/ES20/Core.cs \
	src/MiniTK/Graphics/ES20/ErrorHelper.cs \
	src/MiniTK/Graphics/ES20/Enums.cs \
	src/MiniTK/Graphics/ES20/Delegates.cs \
	src/MiniTK/Graphics/ES20/Helper.cs \
	src/MiniTK/Graphics/ES20/ES.cs \
	src/MiniTK/Graphics/GraphicsContextMissingException.cs \
	src/MiniTK/Graphics/OpenGL/GLDelegates.cs \
	src/MiniTK/Graphics/OpenGL/GLCore.cs \
	src/MiniTK/Graphics/OpenGL/ErrorHelper.cs \
	src/MiniTK/Graphics/OpenGL/GLHelper.cs \
	src/MiniTK/Graphics/OpenGL/GL.cs \
	src/MiniTK/Graphics/OpenGL/GLEnums.cs \
	src/MiniTK/Graphics/ES10/Core.cs \
	src/MiniTK/Graphics/ES10/ErrorHelper.cs \
	src/MiniTK/Graphics/ES10/Enums.cs \
	src/MiniTK/Graphics/ES10/Delegates.cs \
	src/MiniTK/Graphics/ES10/Helper.cs \
	src/MiniTK/Graphics/ES10/ES.cs \
	src/MiniTK/Graphics/ES11/Core.cs \
	src/MiniTK/Graphics/ES11/ErrorHelper.cs \
	src/MiniTK/Graphics/ES11/Enums.cs \
	src/MiniTK/Graphics/ES11/Delegates.cs \
	src/MiniTK/Graphics/ES11/Helper.cs \
	src/MiniTK/Graphics/ES11/ES.cs \
	src/MiniTK/Graphics/SDL2_GraphicsContext.cs \
	src/MiniTK/Graphics/Color4.cs \
	src/MiniTK/Graphics/GraphicsContextException.cs \
	src/MiniTK/Graphics/GraphicsErrorException.cs \
	src/MiniTK/Graphics/GraphicsExceptions.cs \
	src/MiniTK/BindingsBase.cs \
	src/MiniTK/Audio/AudioCapture.cs \
	src/MiniTK/Audio/AudioContextException.cs \
	src/MiniTK/Audio/AudioException.cs \
	src/MiniTK/Audio/OpenAL/Alc/Alc.cs \
	src/MiniTK/Audio/OpenAL/Alc/AlcEnums.cs \
	src/MiniTK/Audio/OpenAL/AL/EffectsExtensionEnums.cs \
	src/MiniTK/Audio/OpenAL/AL/EffectsExtension.cs \
	src/MiniTK/Audio/OpenAL/AL/AL.cs \
	src/MiniTK/Audio/OpenAL/AL/XRamExtension.cs \
	src/MiniTK/Audio/OpenAL/AL/EffectsExtensionPresets.cs \
	src/MiniTK/Audio/OpenAL/AL/ALEnums.cs \
	src/MiniTK/Audio/AudioContext.cs \
	src/MiniTK/Audio/AudioValueException.cs \
	src/MiniTK/Audio/AudioDeviceErrorChecker.cs \
	src/MiniTK/Audio/AudioDeviceEnumerator.cs \
	src/MiniTK/Audio/AudioDeviceException.cs

# Targets

build: clean
	mkdir bin
	cp SDL2#.dll.config bin
	dmcs /unsafe -debug -out:bin/SDL2#.dll -target:library $(SDL2) $(MINITK) $(DEPS)

clean:
	rm -rf bin
