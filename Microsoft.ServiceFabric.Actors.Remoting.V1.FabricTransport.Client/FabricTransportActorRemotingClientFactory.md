<Type Name="FabricTransportActorRemotingClientFactory" FullName="Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory">
  <TypeSignature Language="C#" Value="public class FabricTransportActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportActorRemotingClientFactory extends Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportActorRemotingClientFactory&#xA;Inherits FabricTransportServiceRemotingClientFactory" />
  <TypeSignature Language="F#" Value="type FabricTransportActorRemotingClientFactory = class&#xA;    inherit FabricTransportServiceRemotingClientFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> , die Fabric-TCP-Transport verwendet, erstellen Sie <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" /> , kommunizieren über Schnittstellen, die über Remote sind mit Akteure <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportActorRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory.#ctor(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (callbackClient As IServiceRemotingCallbackClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory callbackClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">
                Der Rückruf-Client, der die Rückrufe vom Dienst empfängt.
            </param>
        <summary>
            Erstellt eine Fabric Transport basierend Akteur Remoting-Client-Factory.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportActorRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings fabricTransportRemotingSettings, Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, string traceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings fabricTransportRemotingSettings, class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory.#ctor(Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings,Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings * Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * string -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory (fabricTransportRemotingSettings, callbackClient, servicePartitionResolver, exceptionHandlers, traceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fabricTransportRemotingSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" />
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fabricTransportRemotingSettings">
                Die Einstellungen für die Fabric-Transport. Wenn die Einstellungen nicht angegeben oder null, Standardeinstellungen ohne Sicherheit sind.
                </param>
        <param name="callbackClient">
                Der Rückruf-Client, der die Rückrufe vom Dienst empfängt.
            </param>
        <param name="servicePartitionResolver">
                Partition-Konfliktlöser auf die Dienst-Endpunkten zu beheben. Wenn nicht angegeben ist, ein Standarddienst-Konfliktlöser Partition zurückgegebenes <see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" /> verwendet wird.
                </param>
        <param name="exceptionHandlers">
                Der Ausnahmehandler behandelt die Ausnahmen, die bei der Kommunikation mit dem Akteur gefunden.
            </param>
        <param name="traceId">
                ID, bei der Diagnose ablaufverfolgungen dieser Komponente verwendet.
            </param>
        <summary>
            Erstellt eine Fabric Transport basierend Akteur Remoting-Client-Factory.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>