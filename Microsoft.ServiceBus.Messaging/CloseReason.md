<Type Name="CloseReason" FullName="Microsoft.ServiceBus.Messaging.CloseReason">
  <TypeSignature Language="C#" Value="public enum CloseReason" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CloseReason extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.CloseReason" />
  <TypeSignature Language="VB.NET" Value="Public Enum CloseReason" />
  <TypeSignature Language="F#" Value="type CloseReason = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="6b1f2-101">Listet den Grund für das Schließen der Sitzung.</span><span class="sxs-lookup"><span data-stu-id="6b1f2-101">Enumerates the reason for closing of session.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LeaseLost">
      <MemberSignature Language="C#" Value="LeaseLost" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.CloseReason LeaseLost = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.CloseReason.LeaseLost" />
      <MemberSignature Language="VB.NET" Value="LeaseLost" />
      <MemberSignature Language="F#" Value="LeaseLost = 1" Usage="Microsoft.ServiceBus.Messaging.CloseReason.LeaseLost" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.CloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="6b1f2-102">Gibt an, dass die aktuelle Lease unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="6b1f2-102">Specifies that the current lease has been lost.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Shutdown">
      <MemberSignature Language="C#" Value="Shutdown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.CloseReason Shutdown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.CloseReason.Shutdown" />
      <MemberSignature Language="VB.NET" Value="Shutdown" />
      <MemberSignature Language="F#" Value="Shutdown = 0" Usage="Microsoft.ServiceBus.Messaging.CloseReason.Shutdown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.CloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="6b1f2-103">Gibt an, dass der Server heruntergefahren wird.</span><span class="sxs-lookup"><span data-stu-id="6b1f2-103">Specifies that the server is shutting down.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>