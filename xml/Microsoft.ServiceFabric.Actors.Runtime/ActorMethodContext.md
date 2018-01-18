<Type Name="ActorMethodContext" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext">
  <TypeSignature Language="C#" Value="public struct ActorMethodContext" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit ActorMethodContext extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />
  <TypeSignature Language="VB.NET" Value="Public Structure ActorMethodContext" />
  <TypeSignature Language="F#" Value="type ActorMethodContext = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="07189-101">Enthält Informationen über die Methode, die vom Akteur Laufzeit aufgerufen wird, und wird als Argument übergeben <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" /> und <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />.</span><span class="sxs-lookup"><span data-stu-id="07189-101">Contains information about the method that is invoked by actor runtime and is passed as an argument to <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" /> and <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CallType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorCallType CallType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorCallType CallType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext.CallType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CallType As ActorCallType" />
      <MemberSignature Language="F#" Value="member this.CallType : Microsoft.ServiceFabric.Actors.Runtime.ActorCallType" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext.CallType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorCallType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07189-102">Ruft den Typ des Aufrufs von Akteur-Laufzeit (z. B. Schnittstellenmethode Akteur, Zeitgeberrückruf usw.).</span><span class="sxs-lookup"><span data-stu-id="07189-102">Gets the type of call by actor runtime (e.g. actor interface method, timer callback etc.).</span></span>
            </summary>
        <value>
            <span data-ttu-id="07189-103">Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType" /> der Aufruftyp darstellt.</span><span class="sxs-lookup"><span data-stu-id="07189-103">An <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType" /> representing the call type.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MethodName">
      <MemberSignature Language="C#" Value="public string MethodName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MethodName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext.MethodName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MethodName As String" />
      <MemberSignature Language="F#" Value="member this.MethodName : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext.MethodName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07189-104">Ruft den Namen der Methode, die vom Akteur Laufzeit aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="07189-104">Gets the name of the method invoked by actor runtime.</span></span>
            </summary>
        <value><span data-ttu-id="07189-105">Der Name der Methode.</span><span class="sxs-lookup"><span data-stu-id="07189-105">The name of method.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>