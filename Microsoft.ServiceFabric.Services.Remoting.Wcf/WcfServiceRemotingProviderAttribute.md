<Type Name="WcfServiceRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public sealed class WcfServiceRemotingProviderAttribute : Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WcfServiceRemotingProviderAttribute extends Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WcfServiceRemotingProviderAttribute&#xA;Inherits ServiceRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type WcfServiceRemotingProviderAttribute = class&#xA;    inherit ServiceRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
                Legt die WCF als Standard-Remoting Transport Dienstanbieter in der Assembly fest.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute" /> die festzulegende WCF-Transport als Standard-Remoting Transport Dienstanbieter in der Assembly verwendet werden können.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseTimeoutInMilliSeconds">
      <MemberSignature Language="C#" Value="public long CloseTimeoutInMilliSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CloseTimeoutInMilliSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CloseTimeoutInMilliSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property CloseTimeoutInMilliSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.CloseTimeoutInMilliSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CloseTimeoutInMilliSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                Ruft ab oder legt den Timeout in Millisekunden vor dem Schließen der Verbindung mit vorhandenen Nachrichten abzuleiten.
            </summary>
        <value>
                Das Timeout in Millisekunden, die vor dem Schließen der Verbindung um eine vorhandene Ausgleichsmodus Nachrichten warten.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="wcfServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">
                Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.
            </param>
        <summary>
                Erstellt eine Factory V1 Dienst Remoting-Client, der verwendet werden kann die <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> um einen Proxy für die Remoteschnittstelle des Diensts zu erstellen.
                </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Client.WcfServiceRemotingClientFactory" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="wcfServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">
                Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.
            </param>
        <summary>
                Erstellt eine Dienst-Remoting-Client-Factory, die verwendet werden kann die <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> um einen Proxy für die Remoteschnittstelle des Diensts zu erstellen.
                </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Client.WcfServiceRemotingClientFactory" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CreateServiceRemotingListener(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="wcfServiceRemotingProviderAttribute.CreateServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="serviceImplementation">
                Das Dienstobjekt für die Implementierung.
            </param>
        <summary>
                Erstellt einen V1 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Wcf.Runtime.WcfServiceRemotingListener" /> für den angegebenen Dienst.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="wcfServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2 (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="serviceImplementation">
                Das Dienstobjekt für die Implementierung.
            </param>
        <summary>
                Erstellt einen V2 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" /> für den angegebenen Dienst.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                Ruft ab oder legt die maximale Nachrichtengröße, die über Remoting übertragen werden kann.
            </summary>
        <value>
                Die maximale Nachrichtengröße, die über Remoting übertragen werden kann.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenTimeoutInMilliSeconds">
      <MemberSignature Language="C#" Value="public long OpenTimeoutInMilliSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OpenTimeoutInMilliSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.OpenTimeoutInMilliSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OpenTimeoutInMilliSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OpenTimeoutInMilliSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.Wcf.WcfServiceRemotingProviderAttribute.OpenTimeoutInMilliSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                Ruft ab oder legt den Timeout in Millisekunden für das Öffnen der Verbindung von Clientseite und wartet auf den Listener, auf der Dienstseite zu öffnen.
            </summary>
        <value>
                Das Timeout in Millisekunden für das Öffnen der Verbindung von Clientseite und wartet auf den Listener, auf der Dienstseite zu öffnen.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>