<Type Name="ActorRemotingDispatchHeaders" FullName="Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders">
  <TypeSignature Language="C#" Value="public class ActorRemotingDispatchHeaders : Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorRemotingDispatchHeaders extends Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorRemotingDispatchHeaders&#xA;Inherits ServiceRemotingDispatchHeaders" />
  <TypeSignature Language="F#" Value="type ActorRemotingDispatchHeaders = class&#xA;    inherit ServiceRemotingDispatchHeaders" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gibt die Header an, die zusammen mit einer Meldung ServiceRemoting gesendet werden. Diese Klasse wird verwendet, mit dem Dienst unabhängig vom Verteiler <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Runtime.ActorServiceRemotingDispatcher" /> . z. B. verkürzte (wenn Client und Dienst sind in demselben Prozess)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorRemotingDispatchHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.ActorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Akteur-ID an, welche Remoting Anforderung Dispatch ist
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorInterfaceName">
      <MemberSignature Language="C#" Value="public string ActorInterfaceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActorInterfaceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.ActorInterfaceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorInterfaceName As String" />
      <MemberSignature Language="F#" Value="member this.ActorInterfaceName : string with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.ActorInterfaceName" />
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
            Dies ist der vollständige Name für die IActor-Benutzeroberfläche.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CallContext">
      <MemberSignature Language="C#" Value="public string CallContext { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CallContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.CallContext" />
      <MemberSignature Language="VB.NET" Value="Public Property CallContext As String" />
      <MemberSignature Language="F#" Value="member this.CallContext : string with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.V2.ActorRemotingDispatchHeaders.CallContext" />
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
            Dies wird verwendet, um des Wiedereintritts in Akteuren zu beschränken. Dies ist ein optionaler Header. Wenn nicht angegeben. Überprüft, ob vorhandene CallContext und fügt an die Guid an, und verwenden es als ein CallContext für diese Anforderung.
            Wenn vorhandene CallContext nicht vorhanden ist, wird darauf Zufalls-Guid zugewiesen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>