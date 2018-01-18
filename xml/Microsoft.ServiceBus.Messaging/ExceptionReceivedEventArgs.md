<Type Name="ExceptionReceivedEventArgs" FullName="Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs">
  <TypeSignature Language="C#" Value="public sealed class ExceptionReceivedEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionReceivedEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionReceivedEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type ExceptionReceivedEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="89bbf-101">Stellt Daten für das <see cref="E:Microsoft.ServiceBus.Messaging.OnMessageOptions.ExceptionReceived" />-Ereignis bereit.</span><span class="sxs-lookup"><span data-stu-id="89bbf-101">Provides data for the <see cref="E:Microsoft.ServiceBus.Messaging.OnMessageOptions.ExceptionReceived" /> event.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionReceivedEventArgs (Exception exception, string action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.#ctor(System.Exception,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs : Exception * string -&gt; Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs" Usage="new Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs (exception, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="action" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="89bbf-102">Die Ausnahme, der diese Ereignisdaten gehört.</span><span class="sxs-lookup"><span data-stu-id="89bbf-102">The exception that this event data belongs to.</span></span></param>
        <param name="action"><span data-ttu-id="89bbf-103">Die Aktion, die dem Ereignis zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="89bbf-103">The action associated with the event.</span></span></param>
        <summary><span data-ttu-id="89bbf-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="89bbf-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string" Usage="Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89bbf-105">Ruft die Aktion, die dem Ereignis zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="89bbf-105">Gets the action associated with the event.</span></span></summary>
        <value><span data-ttu-id="89bbf-106">Die Aktion, die dem Ereignis zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="89bbf-106">The action associated with the event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="89bbf-107">Ruft das übergeordnete Element-Klassenausnahme aus, zu dem diese Ereignisdaten gehört.</span><span class="sxs-lookup"><span data-stu-id="89bbf-107">Gets the parent class exception to which this event data belongs.</span></span></summary>
        <value><span data-ttu-id="89bbf-108">Die Ausnahme, der generiert durch die übergeordnete Klasse, zu der diese Ereignisdaten gehört.</span><span class="sxs-lookup"><span data-stu-id="89bbf-108">The exception, generated by the parent class, to which this event data belongs.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>