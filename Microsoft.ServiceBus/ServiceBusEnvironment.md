<Type Name="ServiceBusEnvironment" FullName="Microsoft.ServiceBus.ServiceBusEnvironment">
  <TypeSignature Language="C#" Value="public static class ServiceBusEnvironment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceBusEnvironment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ServiceBusEnvironment" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusEnvironment" />
  <TypeSignature Language="F#" Value="type ServiceBusEnvironment = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Beschreibt die Service Bus-Umgebung. </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAccessControlUri">
      <MemberSignature Language="C#" Value="public static Uri CreateAccessControlUri (string serviceNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateAccessControlUri(string serviceNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusEnvironment.CreateAccessControlUri(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAccessControlUri (serviceNamespace As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateAccessControlUri : string -&gt; Uri" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.CreateAccessControlUri serviceNamespace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceNamespace">So erstellen den URI für Service-Namespace.</param>
        <summary>Erstellt eine URI-Zeichenfolge mit der Zugriffssteuerung für den angegebenen Dienstnamespace zu verwenden.</summary>
        <returns>Gibt eine <see cref="T:System.Uri" /> , die den angegebenen URI enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string -&gt; Uri" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheme" Type="System.String" />
        <Parameter Name="serviceNamespace" Type="System.String" />
        <Parameter Name="servicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scheme">Das URI-Schema.</param>
        <param name="serviceNamespace">Der Dienstnamespace, die von der Anwendung verwendet.</param>
        <param name="servicePath">Der Pfad des Diensts, der im Abschnitt des Host-Name des URIS folgt.</param>
        <summary>Erstellt den Service Bus-URI für eine Anwendung mit angegebenem Schema, Service-Namespace und der Dienstpfad an.</summary>
        <returns>Gibt eine <see cref="T:System.Uri" /> , die den neuen URI enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String, suppressRelayPathPrefix As Boolean) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string * bool -&gt; Uri" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath, suppressRelayPathPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheme" Type="System.String" />
        <Parameter Name="serviceNamespace" Type="System.String" />
        <Parameter Name="servicePath" Type="System.String" />
        <Parameter Name="suppressRelayPathPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scheme">Das URI-Schema.</param>
        <param name="serviceNamespace">Der Dienstnamespace, die von der Anwendung verwendet.</param>
        <param name="servicePath">Der Pfad des Diensts, der im Abschnitt des Host-Name des URIS folgt.</param>
        <param name="suppressRelayPathPrefix">True, wenn der Relay-Pfadpräfix unterdrückt wird. andernfalls "false".</param>
        <summary>Erstellt den Service Bus-URI für eine Anwendung unter Verwendung der angegebenen Schema, Service-Namespace, Dienstpfad und Pfadpräfix weitergeleitet.</summary>
        <returns>Gibt eine <see cref="T:System.Uri" /> , die den neuen URI enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultIdentityHostName">
      <MemberSignature Language="C#" Value="public static string DefaultIdentityHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string DefaultIdentityHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultIdentityHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultIdentityHostName : string" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Standardhostnamen für Access Control Service ab.</summary>
        <value>Gibt den Standardhostnamen der Identität zurück. </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.ConnectivitySettings SystemConnectivity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.ConnectivitySettings SystemConnectivity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusEnvironment.SystemConnectivity" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property SystemConnectivity As ConnectivitySettings" />
      <MemberSignature Language="F#" Value="member this.SystemConnectivity : Microsoft.ServiceBus.ConnectivitySettings" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.SystemConnectivity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivitySettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Singleton ab <see cref="T:Microsoft.ServiceBus.ConnectivitySettings" /> -Instanz, die die Konnektivitätseinstellungen für TCP und HTTP basierenden Endpunkte enthält.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.ConnectivitySettings" /> , enthält die Einstellungen für die Netzwerkkonnektivität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>