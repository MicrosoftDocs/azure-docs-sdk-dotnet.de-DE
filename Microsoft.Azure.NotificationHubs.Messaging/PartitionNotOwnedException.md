<Type Name="PartitionNotOwnedException" FullName="Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException">
  <TypeSignature Language="C#" Value="public sealed class PartitionNotOwnedException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit PartitionNotOwnedException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionNotOwnedException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type PartitionNotOwnedException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die Ausnahme, die für eine anzeigenden Partition, deren Besitzer er nicht Fehler ausgelöst wird.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionNotOwnedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die Fehlermeldung, die die Ursache der Ausnahme beschreibt.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" />-Klasse mit einer angegebenen Fehlermeldung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionNotOwnedException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">Die Fehlermeldung, die die Ursache der Ausnahme beschreibt.</param>
        <param name="innerException">Die innere Ausnahme, die die Ursache der aktuellen Ausnahme ist.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>