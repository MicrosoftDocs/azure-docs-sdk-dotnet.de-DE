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
            Enthält Informationen über die Methode, die vom Akteur Laufzeit aufgerufen wird, und wird als Argument übergeben <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" /> und <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />.
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
            Ruft den Typ des Aufrufs von Akteur-Laufzeit (z. B. Schnittstellenmethode Akteur, Zeitgeberrückruf usw.).
            </summary>
        <value>
            Ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType" /> der Aufruftyp darstellt.
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
            Ruft den Namen der Methode, die vom Akteur Laufzeit aufgerufen.
            </summary>
        <value>Der Name der Methode.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>