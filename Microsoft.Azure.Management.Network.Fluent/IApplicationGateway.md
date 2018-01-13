<Type Name="IApplicationGateway" FullName="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway">
  <TypeSignature Language="C#" Value="public interface IApplicationGateway : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBeta, Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationGateway implements class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBeta, class Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationGateway&#xA;Implements IApplicationGatewayBeta, IBeta, IGroupableResource(Of INetworkManager, ApplicationGatewayInner), IHasInner(Of ApplicationGatewayInner), IHasManager(Of INetworkManager), IHasPrivateIPAddress, IHasSubnet, IRefreshable(Of IApplicationGateway), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IApplicationGateway = interface&#xA;    interface IGroupableResource&lt;INetworkManager, ApplicationGatewayInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;INetworkManager&gt;&#xA;    interface IHasInner&lt;ApplicationGatewayInner&gt;&#xA;    interface IRefreshable&lt;IApplicationGateway&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;&#xA;    interface IHasSubnet&#xA;    interface IHasPrivateIPAddress&#xA;    interface IApplicationGatewayBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Einstiegspunkt für Application Gateway Management API in Azure.
            </summary>
    <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="BackendHttpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration&gt; BackendHttpConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration&gt; BackendHttpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.BackendHttpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendHttpConfigurations As IReadOnlyDictionary(Of String, IApplicationGatewayBackendHttpConfiguration)" />
      <MemberSignature Language="F#" Value="member this.BackendHttpConfigurations : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.BackendHttpConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Back-End-HTTP-Konfigurationen von diesem Anwendungsgateway nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend&gt; Backends { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend&gt; Backends" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Backends" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Backends As IReadOnlyDictionary(Of String, IApplicationGatewayBackend)" />
      <MemberSignature Language="F#" Value="member this.Backends : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Backends" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackend&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Back-End-Adresspools des Application-Gateways, nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration DefaultIPConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration DefaultIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.DefaultIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultIPConfiguration As IApplicationGatewayIPConfiguration" />
      <MemberSignature Language="F#" Value="member this.DefaultIPConfiguration : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.DefaultIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die IP-Konfiguration mit dem Namen "Default", falls vorhanden, oder die ruft IP-Konfiguration vorhandene Wenn nur eine vorhanden ist, andernfalls Null.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend DefaultPrivateFrontend { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend DefaultPrivateFrontend" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.DefaultPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultPrivateFrontend As IApplicationGatewayFrontend" />
      <MemberSignature Language="F#" Value="member this.DefaultPrivateFrontend : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.DefaultPrivateFrontend" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Front-End-IP-Konfiguration mit einer privaten IP-Adresse zugeordnet ist, wenn vorhanden, die Front-End-Listener und Anforderung Routingregeln implizit verweisen können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend DefaultPublicFrontend { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend DefaultPublicFrontend" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.DefaultPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultPublicFrontend As IApplicationGatewayFrontend" />
      <MemberSignature Language="F#" Value="member this.DefaultPublicFrontend : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.DefaultPublicFrontend" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Front-End-IP-Konfiguration mit einer öffentlichen IP-Adresse zugeordnet ist, wenn vorhanden, die Front-End-Listener und Anforderung Routingregeln implizit verweisen können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortNameFromNumber">
      <MemberSignature Language="C#" Value="public string FrontendPortNameFromNumber (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string FrontendPortNameFromNumber(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.FrontendPortNameFromNumber(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FrontendPortNameFromNumber (portNumber As Integer) As String" />
      <MemberSignature Language="F#" Value="abstract member FrontendPortNameFromNumber : int -&gt; string" Usage="iApplicationGateway.FrontendPortNameFromNumber portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">eine Portnummer an.</param>
        <summary>
            Gibt den Namen der vorhandenen Port zurück, falls vorhanden, die die angegebene Portnummer zugeordnet ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die vorhandene Port für die entsprechende Portnummer nennen, oder null, wenn keiner gefunden.</return>
      </Docs>
    </Member>
    <Member MemberName="FrontendPorts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,int&gt; FrontendPorts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, int32&gt; FrontendPorts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.FrontendPorts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FrontendPorts As IReadOnlyDictionary(Of String, Integer)" />
      <MemberSignature Language="F#" Value="member this.FrontendPorts : System.Collections.Generic.IReadOnlyDictionary&lt;string, int&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.FrontendPorts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Front-End-Ports des Application-Gateways, nach Namen indiziert benannt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frontends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt; Frontends { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt; Frontends" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Frontends" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Frontends As IReadOnlyDictionary(Of String, IApplicationGatewayFrontend)" />
      <MemberSignature Language="F#" Value="member this.Frontends : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Frontends" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Front-End-IP-Konfigurationen, die nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceCount">
      <MemberSignature Language="C#" Value="public int InstanceCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 InstanceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.InstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceCount As Integer" />
      <MemberSignature Language="F#" Value="member this.InstanceCount : int" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.InstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Instanzen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration&gt; IPConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration&gt; IPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.IPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IPConfigurations As IReadOnlyDictionary(Of String, IApplicationGatewayIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.IPConfigurations : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.IPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IP-Konfigurationen des Application-Gateways, nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivate">
      <MemberSignature Language="C#" Value="public bool IsPrivate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPrivate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.IsPrivate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPrivate As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPrivate : bool" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.IsPrivate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn das Application Gateway wurde mindestens eine ausgeglichene Front-End innerhalb des virtuellen Netzwerks zugegriffen werden intern laden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPublic">
      <MemberSignature Language="C#" Value="public bool IsPublic { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPublic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.IsPublic" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPublic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPublic : bool" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.IsPublic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, true, wenn das Anwendungsgateway mindestens Internet zugewandten Front-End-aufweist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerByPortNumber">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayListener ListenerByPortNumber (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayListener ListenerByPortNumber(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.ListenerByPortNumber(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListenerByPortNumber (portNumber As Integer) As IApplicationGatewayListener" />
      <MemberSignature Language="F#" Value="abstract member ListenerByPortNumber : int -&gt; Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayListener" Usage="iApplicationGateway.ListenerByPortNumber portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">Eine verwendete Portnummer an.</param>
        <summary>
            Sucht einen Front-End-Listener, die ggf. die angegebene Front-End-Port-Nummer zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Ein Front-End-Listener oder Null, wenn keiner gefunden wird.</return>
      </Docs>
    </Member>
    <Member MemberName="Listeners">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayListener&gt; Listeners { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayListener&gt; Listeners" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Listeners" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Listeners As IReadOnlyDictionary(Of String, IApplicationGatewayListener)" />
      <MemberSignature Language="F#" Value="member this.Listeners : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayListener&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Listeners" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayListener&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Front-End-Listener, die nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationalState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayOperationalState OperationalState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayOperationalState OperationalState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.OperationalState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationalState As ApplicationGatewayOperationalState" />
      <MemberSignature Language="F#" Value="member this.OperationalState : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayOperationalState" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.OperationalState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayOperationalState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Betriebsstatus des Anwendungsgateways ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateFrontends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt; PrivateFrontends { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt; PrivateFrontends" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.PrivateFrontends" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrivateFrontends As IReadOnlyDictionary(Of String, IApplicationGatewayFrontend)" />
      <MemberSignature Language="F#" Value="member this.PrivateFrontends : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.PrivateFrontends" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Front-End-IP-Konfigurationen mit einer privaten IP-Adresse in einem Subnetz, die nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe&gt; Probes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe&gt; Probes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Probes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Probes As IReadOnlyDictionary(Of String, IApplicationGatewayProbe)" />
      <MemberSignature Language="F#" Value="member this.Probes : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Probes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Prüfpunkte des Application-Gateways, nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicFrontends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt; PublicFrontends { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt; PublicFrontends" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.PublicFrontends" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicFrontends As IReadOnlyDictionary(Of String, IApplicationGatewayFrontend)" />
      <MemberSignature Language="F#" Value="member this.PublicFrontends : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.PublicFrontends" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Front-End-IP-Konfigurationen mit einer öffentlichen IP-Adresse, nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestRoutingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayRequestRoutingRule&gt; RequestRoutingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayRequestRoutingRule&gt; RequestRoutingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.RequestRoutingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestRoutingRules As IReadOnlyDictionary(Of String, IApplicationGatewayRequestRoutingRule)" />
      <MemberSignature Language="F#" Value="member this.RequestRoutingRules : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayRequestRoutingRule&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.RequestRoutingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayRequestRoutingRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft anfordern Routingregeln, nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As ApplicationGatewaySkuName" />
      <MemberSignature Language="F#" Value="member this.Size : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Größe des Anwendungsgateways ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As ApplicationGatewaySku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die SKU des dieses Anwendungsgateway ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaySslCertificate&gt; SslCertificates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaySslCertificate&gt; SslCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.SslCertificates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SslCertificates As IReadOnlyDictionary(Of String, IApplicationGatewaySslCertificate)" />
      <MemberSignature Language="F#" Value="member this.SslCertificates : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaySslCertificate&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.SslCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaySslCertificate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die SSL-Zertifikate, die nach Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iApplicationGateway.Start " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet das Anwendungsgateway.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iApplicationGateway.StartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Startet das Anwendungsgateway asynchron aus.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public void Stop ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Stop() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Stop" />
      <MemberSignature Language="VB.NET" Value="Public Sub Stop ()" />
      <MemberSignature Language="F#" Value="abstract member Stop : unit -&gt; unit" Usage="iApplicationGateway.Stop " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Beendet das Anwendungsgateway.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StopAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.StopAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iApplicationGateway.StopAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Das Anwendungsgateway beendet asynchron.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayTier Tier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayTier Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Tier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tier As ApplicationGatewayTier" />
      <MemberSignature Language="F#" Value="member this.Tier : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayTier" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGateway.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayTier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ebene für das Anwendungsgateway ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>