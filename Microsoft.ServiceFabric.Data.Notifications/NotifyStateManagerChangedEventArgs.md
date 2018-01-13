<Type Name="NotifyStateManagerChangedEventArgs" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs">
  <TypeSignature Language="C#" Value="public abstract class NotifyStateManagerChangedEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NotifyStateManagerChangedEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NotifyStateManagerChangedEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type NotifyStateManagerChangedEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6ea4e-101">Stellt Daten für das StateManagerChanged-Ereignis.</span><span class="sxs-lookup"><span data-stu-id="6ea4e-101">Provides data for the StateManagerChanged event.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyStateManagerChangedEventArgs (Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs.#ctor(Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (action As NotifyStateManagerChangedAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs : Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs action" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="action" Type="Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction" />
      </Parameters>
      <Docs>
        <param name="action"><span data-ttu-id="6ea4e-102">Der Typ des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="6ea4e-102">Type of the event.</span></span></param>
        <summary>
            <span data-ttu-id="6ea4e-103">Initialisiert eine neue Instanz der dem<cref name="NotifyStateManagerChangedEventArgs" /></span><span class="sxs-lookup"><span data-stu-id="6ea4e-103">Initializes a new instance of the <cref name="NotifyStateManagerChangedEventArgs" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As NotifyStateManagerChangedAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ea4e-104">Ruft die Aktion ab, die das Ereignis verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="6ea4e-104">Gets the action that caused the event.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6ea4e-105">Der Typ der Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6ea4e-105">The type of notification.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>