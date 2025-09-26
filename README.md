MDK.Build.BuildException: Error loading script projects from H:\Games\Space Engineers\Skripts\ource\repos\IngameScript1\IngameScript1.sln ---> System.TimeoutException: Timeout für den Vorgang wurde überschritten.
   bei System.IO.Pipes.NamedPipeClientStream.Connect(Int32 timeout)
   bei Microsoft.CodeAnalysis.MSBuild.BuildHostProcessManager.BuildHostProcess..ctor(Process process, String pipeName, ILoggerFactory loggerFactory)
   bei Microsoft.CodeAnalysis.MSBuild.BuildHostProcessManager.<GetBuildHostAsync>d__9.MoveNext()
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei System.Runtime.CompilerServices.TaskAwaiter.HandleNonSuccessAndDebuggerNotification(Task task)
   bei Microsoft.CodeAnalysis.MSBuild.BuildHostProcessManager.<GetBuildHostWithFallbackAsync>d__8.MoveNext()
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei System.Runtime.CompilerServices.TaskAwaiter.HandleNonSuccessAndDebuggerNotification(Task task)
   bei Microsoft.CodeAnalysis.MSBuild.MSBuildProjectLoader.Worker.<LoadProjectFileInfosAsync>d__20.MoveNext()
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei System.Runtime.CompilerServices.TaskAwaiter.HandleNonSuccessAndDebuggerNotification(Task task)
   bei Microsoft.CodeAnalysis.MSBuild.MSBuildProjectLoader.Worker.<LoadProjectInfosFromPathAsync>d__21.MoveNext()
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei Microsoft.CodeAnalysis.MSBuild.MSBuildProjectLoader.Worker.<LoadAsync>d__19.MoveNext()
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei System.Runtime.CompilerServices.TaskAwaiter.HandleNonSuccessAndDebuggerNotification(Task task)
   bei Microsoft.CodeAnalysis.MSBuild.MSBuildProjectLoader.<LoadSolutionInfoAsync>d__23.MoveNext()
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei Microsoft.CodeAnalysis.MSBuild.MSBuildProjectLoader.<LoadSolutionInfoAsync>d__23.MoveNext()
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei System.Runtime.CompilerServices.TaskAwaiter.HandleNonSuccessAndDebuggerNotification(Task task)
   bei Microsoft.CodeAnalysis.MSBuild.MSBuildWorkspace.<OpenSolutionAsync>d__26.MoveNext()
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei System.Runtime.CompilerServices.TaskAwaiter.HandleNonSuccessAndDebuggerNotification(Task task)
   bei MDK.Build.BuildModule.<LoadScriptProjectsAsync>d__26.MoveNext() in D:\Repos\SpaceEngineers\MDK-SE\Source\MDK\Build\BuildModule.cs:Zeile 131.
   --- Ende der internen Ausnahmestapelüberwachung ---
   bei MDK.Build.BuildModule.<LoadScriptProjectsAsync>d__26.MoveNext() in D:\Repos\SpaceEngineers\MDK-SE\Source\MDK\Build\BuildModule.cs:Zeile 138.
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei System.Runtime.CompilerServices.TaskAwaiter.HandleNonSuccessAndDebuggerNotification(Task task)
   bei MDK.Build.BuildModule.<<RunAsync>b__25_0>d.MoveNext() in D:\Repos\SpaceEngineers\MDK-SE\Source\MDK\Build\BuildModule.cs:Zeile 117.
--- Ende der Stapelüberwachung vom vorhergehenden Ort, an dem die Ausnahme ausgelöst wurde ---
   bei System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()
   bei System.Runtime.CompilerServices.TaskAwaiter.HandleNonSuccessAndDebuggerNotification(Task task)
   bei MDK.MDKPackage.<DeployAsync>d__47.MoveNext() in D:\Repos\SpaceEngineers\MDK-SE\Source\MDK\MDKPackage.cs:Zeile 369.
