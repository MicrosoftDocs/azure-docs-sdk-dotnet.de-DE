<Type Name="ServiceRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public abstract class ServiceRemotingProviderAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceRemotingProviderAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceRemotingProviderAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type ServiceRemotingProviderAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Dies ist ein Basistyp für das Attribut, das legt den Standard-Remoting-Dienstanbieter für das Remoting zu verwenden, die Dienstschnittstellen definiert und in der Assembly verwendet.
            </summary>
    <remarks>
      <para>
                Auf Dienstseite-Implementierung des Attributs gesucht wird durch <see cref="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatefulServiceContext)" /> und <see cref="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatelessServiceContext)" /> Methoden auf die Laufzeit zum Erstellen eines standardmäßigen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für zustandsbehaftete und zustandslose Dienste. 
                </para>
      <para>
                Auf Clientseite-Implementierung des Attributs gesucht wird durch <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> Konstruktor zum Erstellen eines standardmäßigen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> wenn er nicht angegeben wird.
                </para>
      <para>
                Beachten Sie, auf Clientseite <see cref="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxy.Create``1(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String)" /> Methode erstellt einen Standard- <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> einmal und daher die Anbieter-Suche erfolgt, nur zum ersten Mal, wonach die gleiche Anbieter verwendet wird.
                </para>
      <para>
                Die Reihenfolge, in dem dieses Attribut gesucht wird, lautet wie folgt: <list type="number"> <item> im Eintrag <see cref="T:System.Reflection.Assembly" /> durch Aufrufen der Methode abgerufenen <see cref="M:System.Reflection.Assembly.GetEntryAssembly" /> </item> <item> In der <see cref="T:System.Reflection.Assembly" /> , definiert der remote-Schnittstelle für Welche Listener oder Proxy erstellt wird.</item></list></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ServiceRemotingProviderAttribute-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.</param>
        <summary>
            Erstellt eine Dienst-Remoting-Client-Factory, die verwendet werden kann die <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> um einen Proxy für die Remoteschnittstelle des Diensts zu erstellen.
            </summary>
        <returns><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.</param>
        <summary>
            Erstellt eine Factory V2 Dienst Remoting-Client, der verwendet werden kann die <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.ServiceProxyFactory" /> um einen Proxy für die Remoteschnittstelle des Diensts zu erstellen.
            </summary>
        <returns><see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingListener(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</param>
        <param name="serviceImplementation">Das Dienstobjekt für die Implementierung.</param>
        <summary>
            Erstellt einen V1 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für den angegebenen Dienst.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceRemotingListenerV2 : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="serviceRemotingProviderAttribute.CreateServiceRemotingListenerV2 (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</param>
        <param name="serviceImplementation">Das Dienstobjekt für die Implementierung.</param>
        <summary>
            Erstellt einen V2 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für den angegebenen Dienst.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingClient RemotingClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingClient" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingClient As RemotingClient" />
      <MemberSignature Language="F#" Value="member this.RemotingClient : Microsoft.ServiceFabric.Services.Remoting.RemotingClient with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            RemotingClient wird verwendet, um zu bestimmen, wo V1 oder V2 Remoting Client verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingListener">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingListener" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotingListener As RemotingListener" />
      <MemberSignature Language="F#" Value="member this.RemotingListener : Microsoft.ServiceFabric.Services.Remoting.RemotingListener with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute.RemotingListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            RemotingListener wird verwendet, um zu bestimmen, auf dem Listener in V1, V2 oder Komprimierungsmodus ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>