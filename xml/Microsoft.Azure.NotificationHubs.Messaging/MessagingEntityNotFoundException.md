<Type Name="MessagingEntityNotFoundException" FullName="Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException">
  <TypeSignature Language="C#" Value="public sealed class MessagingEntityNotFoundException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingEntityNotFoundException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingEntityNotFoundException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessagingEntityNotFoundException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6bca0-101">Die Ausnahme, die ausgelöst wird, für eine anzeigenden messaging-Entität nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="6bca0-101">The exception that is thrown for signaling messaging entity not found errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityNotFoundException (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (entityName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException entityName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="6bca0-102">Der Name der Entität.</span><span class="sxs-lookup"><span data-stu-id="6bca0-102">The name of the entity.</span></span></param>
        <summary><span data-ttu-id="6bca0-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" /> Klasse mit dem Namen der Entität.</span><span class="sxs-lookup"><span data-stu-id="6bca0-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" /> class with the entity name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityNotFoundException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="6bca0-104">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="6bca0-104">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="6bca0-105">Die Ausnahme, die die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="6bca0-105">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="6bca0-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" />-Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="6bca0-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityNotFoundException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="messagingEntityNotFoundException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6bca0-107">Gibt eine Zeichenfolgendarstellung der aktuellen Ausnahme zurück.</span><span class="sxs-lookup"><span data-stu-id="6bca0-107">Returns a string representation of the current exception.</span></span></summary>
        <returns><span data-ttu-id="6bca0-108">Eine Zeichenfolgendarstellung der aktuellen Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="6bca0-108">A string representation of the current exception.</span></span></returns>
        <remarks>To be added.</remarks>
        <PermissionSet>
          <IPermission class="System.Security.Permissions.FileIOPermission, mscorlib, Version=2.0.3600.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" version="1" PathDiscovery="*AllFiles*" />
        </PermissionSet>
      </Docs>
    </Member>
  </Members>
</Type>