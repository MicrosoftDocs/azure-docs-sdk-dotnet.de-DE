<Type Name="MethodDispatcherBaseWithSerializer" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer">
  <TypeSignature Language="C#" Value="public abstract class MethodDispatcherBaseWithSerializer : Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MethodDispatcherBaseWithSerializer extends Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MethodDispatcherBaseWithSerializer&#xA;Inherits MethodDispatcherBase" />
  <TypeSignature Language="F#" Value="type MethodDispatcherBaseWithSerializer = class&#xA;    inherit MethodDispatcherBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Klasse leitet die Anforderungen vom Client an die Schnittstellenmethode von prozessübergreifendes Objectts.
            Diese Klasse wird vom Code-Generator Remoting verwendet. Diese Klasse wird das Serialisierungsprogramm zwischengespeichert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MethodDispatcherBaseWithSerializer ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueWithResult&lt;TRetval&gt;">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;object&gt; ContinueWithResult&lt;TRetval&gt; (int methodId, System.Threading.Tasks.Task&lt;TRetval&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;object&gt; ContinueWithResult&lt;TRetval&gt;(int32 methodId, class System.Threading.Tasks.Task`1&lt;!!TRetval&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.ContinueWithResult``1(System.Int32,System.Threading.Tasks.Task{``0})" />
      <MemberSignature Language="VB.NET" Value="Protected Function ContinueWithResult(Of TRetval) (methodId As Integer, task As Task(Of TRetval)) As Task(Of Object)" />
      <MemberSignature Language="F#" Value="member this.ContinueWithResult : int * System.Threading.Tasks.Task&lt;'Retval&gt; -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBaseWithSerializer.ContinueWithResult (methodId, task)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRetval" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;TRetval&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TRetval">Rückgabewert</typeparam>
        <param name="methodId">Methode-id</param>
        <param name="task">Fortsetzungsaufgabe</param>
        <summary>
            Intern – von Webdiensten verwendet
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResponseBody">
      <MemberSignature Language="C#" Value="protected abstract object CreateResponseBody (int methodId, object retval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance object CreateResponseBody(int32 methodId, object retval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.CreateResponseBody(System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function CreateResponseBody (methodId As Integer, retval As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member CreateResponseBody : int * obj -&gt; obj" Usage="methodDispatcherBaseWithSerializer.CreateResponseBody (methodId, retval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="retval" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodId">Die ID der Methode.</param>
        <param name="retval">Der Rückgabewert der Methode.</param>
        <summary>
            Diese Methode wird vom Verteiler für die generierte Methode zum Erstellen der Antwort aus dem angegebenen Rückgabewert als Ergebnis verteilen die Methode, die das Remoteobjekt implementiert. 
            </summary>
        <returns>Ein <see cref="T:System.Object">Objekt</see> , die den Antworttext zurück an den Client gesendet werden darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispatch">
      <MemberSignature Language="C#" Value="public override void Dispatch (object objectImplementation, int methodId, object messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Dispatch(object objectImplementation, int32 methodId, object messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.Dispatch(System.Object,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Dispatch (objectImplementation As Object, methodId As Integer, messageBody As Object)" />
      <MemberSignature Language="F#" Value="override this.Dispatch : obj * int * obj -&gt; unit" Usage="methodDispatcherBaseWithSerializer.Dispatch (objectImplementation, methodId, messageBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectImplementation" Type="System.Object" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="messageBody" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="messageBody"></param>
        <summary>
            Diese Methode wird verwendet, eine unidirektionale Nachrichten auf der angegebenen MethodId der Schnittstelle implementiert, die vom Remote-Objekt verteilt wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DispatchAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;object&gt; DispatchAsync (object objectImplementation, int methodId, object requestBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; DispatchAsync(object objectImplementation, int32 methodId, object requestBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.DispatchAsync(System.Object,System.Int32,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.DispatchAsync : obj * int * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBaseWithSerializer.DispatchAsync (objectImplementation, methodId, requestBody, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectImplementation" Type="System.Object" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestBody" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="requestBody"></param>
        <param name="cancellationToken"></param>
        <summary>
            Diese Methode wird verwendet, um dispatch-Anforderung zur angegebenen MethodId der Schnittstelle implementiert, die vom Remote-Objekt.
             </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispatch">
      <MemberSignature Language="C#" Value="protected abstract void OnDispatch (int methodId, object remotedObject, object messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDispatch(int32 methodId, object remotedObject, object messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.OnDispatch(System.Int32,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnDispatch (methodId As Integer, remotedObject As Object, messageBody As Object)" />
      <MemberSignature Language="F#" Value="abstract member OnDispatch : int * obj * obj -&gt; unit" Usage="methodDispatcherBaseWithSerializer.OnDispatch (methodId, remotedObject, messageBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="remotedObject" Type="System.Object" />
        <Parameter Name="messageBody" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodId">Die ID der Methode.</param>
        <param name="remotedObject">Die Instanz prozessübergreifendes Remoteobjekt.</param>
        <param name="messageBody">Nachrichtentext</param>
        <summary>
            Diese Methode wird vom Verteiler für die generierte Methode beim Verteilen von unidirektionaler Nachrichten an der angegebenen MethodId der Schnittstelle implementiert, die vom Remote-Objekt implementiert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispatchAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;object&gt; OnDispatchAsync (int methodId, object remotedObject, object requestBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; OnDispatchAsync(int32 methodId, object remotedObject, object requestBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.OnDispatchAsync(System.Int32,System.Object,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDispatchAsync : int * obj * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBaseWithSerializer.OnDispatchAsync (methodId, remotedObject, requestBody, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="remotedObject" Type="System.Object" />
        <Parameter Name="requestBody" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="methodId">Die ID der Methode.</param>
        <param name="remotedObject">Die Instanz prozessübergreifendes Remoteobjekt.</param>
        <param name="requestBody">Anforderungstext</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese Methode wird vom Verteiler für die generierte Methode auf dispatch-Anforderung zur angegebenen MethodId der durch das Remoteobjekt implementierten Schnittstelle implementiert.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis des Vorgangs ist der Rückgabewert der Methode.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>