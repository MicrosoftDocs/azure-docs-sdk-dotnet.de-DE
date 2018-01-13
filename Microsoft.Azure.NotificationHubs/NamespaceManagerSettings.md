<Type Name="NamespaceManagerSettings" FullName="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManagerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManagerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManagerSettings" />
  <TypeSignature Language="F#" Value="type NamespaceManagerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Enthält die Einstellungen für den NamespaceManager.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManagerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder Festlegen des Zeitlimits Vorgang für alle Namespace dienstverwaltungsvorgänge, wie z. B. GetQueue CreateQueue und So weiter.</summary>
        <value>Ein <see cref="T:System.TimeSpan" /> -Objekt, das Timeout darstellt.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">löst aus, wenn ein NULL-Wert festgelegt ist – z. B. ein NULL-Werte zulassen TimeSpan-Objekt.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">löst aus, wenn eine 0 (null) oder Negative TimeSpan festgelegt ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.NotificationHubs.RetryPolicy with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die basisimplementierung für die wiederholungsversuchmechanismus für unzuverlässige Aktionen und vorübergehende Bedingungen, die dem Namespacemanager zugeordnet.</summary>
        <value>Die basisimplementierung der wiederholungsversuchmechanismus für unzuverlässige Aktionen und vorübergehende Bedingungen, die dem Namespacemanager zugeordnet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt der Anbieter von Sicherheitstoken.</summary>
        <value>Der Sicherheitstokenanbieter.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>