<Type Name="ReceiverOptions" FullName="Microsoft.ServiceBus.Messaging.ReceiverOptions">
  <TypeSignature Language="C#" Value="public class ReceiverOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReceiverOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ReceiverOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ReceiverOptions" />
  <TypeSignature Language="F#" Value="type ReceiverOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="957f4-101">Stellt Optionen können während der Erstellung einer Hub-Ereignisempfänger festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="957f4-101">Represents options can be set during the creation of a event hub receiver.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReceiverOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ReceiverOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverOptions.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.ReceiverOptions.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="957f4-102">Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="957f4-102">Gets or sets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value> <span data-ttu-id="957f4-103">"true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> mit <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="957f4-103">true if a client wants to access <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> using <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverOptions.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string with get, set" Usage="Microsoft.ServiceBus.Messaging.ReceiverOptions.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="957f4-104">Ruft ab oder legt den Bezeichner der einem Empfänger.</span><span class="sxs-lookup"><span data-stu-id="957f4-104">Gets or sets the identifier of a receiver.</span></span></summary>
        <value><span data-ttu-id="957f4-105">Eine Zeichenfolge, die den Bezeichner darstellt, der einen Empfänger.</span><span class="sxs-lookup"><span data-stu-id="957f4-105">A string representing the identifier of a receiver.</span></span>  <span data-ttu-id="957f4-106">Es zurück null, wenn der Bezeichner nicht festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="957f4-106">It will return null if the identifier is not set.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="957f4-107">Wird ausgelöst, wenn die Länge des Werts größer als die maximale Länge von 64 ist.</span><span class="sxs-lookup"><span data-stu-id="957f4-107">Thrown if the length of the value is greater than the maximum length of 64.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>