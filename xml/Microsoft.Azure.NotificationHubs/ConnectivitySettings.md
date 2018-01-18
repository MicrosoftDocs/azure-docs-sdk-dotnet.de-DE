<Type Name="ConnectivitySettings" FullName="Microsoft.Azure.NotificationHubs.ConnectivitySettings">
  <TypeSignature Language="C#" Value="public class ConnectivitySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivitySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ConnectivitySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivitySettings" />
  <TypeSignature Language="F#" Value="type ConnectivitySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="87743-101">Enthält die Verbindungseinstellungen für alle Windows Azure Service Bus-basierte Endpunkte, die in der aktuellen Anwendungsdomäne aktiv sind.</span><span class="sxs-lookup"><span data-stu-id="87743-101">Holds the connectivity settings effective for all Windows Azure Service Bus-based endpoints that are active in the current application domain.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivitySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ConnectivitySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="87743-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivitySettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87743-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivitySettings" /> class.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="connectivityMode">
      <MemberSignature Language="C#" Value="protected Microsoft.Azure.NotificationHubs.ConnectivityMode connectivityMode;" />
      <MemberSignature Language="ILAsm" Value=".field family valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode connectivityMode" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivitySettings.connectivityMode" />
      <MemberSignature Language="VB.NET" Value="Protected connectivityMode As ConnectivityMode " />
      <MemberSignature Language="F#" Value="val mutable connectivityMode : Microsoft.Azure.NotificationHubs.ConnectivityMode" Usage="Microsoft.Azure.NotificationHubs.ConnectivitySettings.connectivityMode" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="87743-103">Enthält die <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivityMode" /> für die aktuelle Instanz.</span><span class="sxs-lookup"><span data-stu-id="87743-103">Contains the <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivityMode" /> for the current instance.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="protected virtual bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ConnectivitySettings.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.Azure.NotificationHubs.ConnectivitySettings.IsReadOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="87743-104">Ruft einen Wert, der bestimmt, ob die Einstellungen für die Netzwerkkonnektivität schreibgeschützt sind.</span><span class="sxs-lookup"><span data-stu-id="87743-104">Gets a value that determines if the connectivity settings are read-only.</span></span> </summary>
        <value><span data-ttu-id="87743-105">"true", wenn die Verbindungseinstellungen schreibgeschützt sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="87743-105">true if the connectivity settings are read-only; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.ConnectivityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ConnectivitySettings.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As ConnectivityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.Azure.NotificationHubs.ConnectivityMode with get, set" Usage="Microsoft.Azure.NotificationHubs.ConnectivitySettings.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="87743-106">Ruft ab oder legt den Verbindungsmodus für die aktuelle Anwendungsdomäne.</span><span class="sxs-lookup"><span data-stu-id="87743-106">Gets or sets the connectivity mode for the current application domain.</span></span> </summary>
        <value><span data-ttu-id="87743-107">Gibt <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivityMode" />. Enthält den Verbindungsmodus.</span><span class="sxs-lookup"><span data-stu-id="87743-107">Returns <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivityMode" />.Contains the connectivity mode.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>