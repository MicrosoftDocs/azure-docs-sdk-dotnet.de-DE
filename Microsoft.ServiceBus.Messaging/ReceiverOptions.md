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
    <summary>Stellt Optionen können während der Erstellung einer Hub-Ereignisempfänger festgelegt werden.</summary>
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
        <summary> Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist. </summary>
        <value> "true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> mit <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />. </value>
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
        <summary>Ruft ab oder legt den Bezeichner der einem Empfänger.</summary>
        <value>Eine Zeichenfolge, die den Bezeichner darstellt, der einen Empfänger.  Es zurück null, wenn der Bezeichner nicht festgelegt ist.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn die Länge des Werts größer als die maximale Länge von 64 ist.</exception>
      </Docs>
    </Member>
  </Members>
</Type>