<Type Name="DeliveryAcknowledgement" FullName="Microsoft.Azure.Devices.DeliveryAcknowledgement">
  <TypeSignature Language="C#" Value="public enum DeliveryAcknowledgement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DeliveryAcknowledgement extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.DeliveryAcknowledgement" />
  <TypeSignature Language="VB.NET" Value="Public Enum DeliveryAcknowledgement" />
  <TypeSignature Language="F#" Value="type DeliveryAcknowledgement = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="34d15-101">Gibt die verschiedenen Empfangsbestätigungsstufen für die Nachrichtenübermittlung an.</span><span class="sxs-lookup"><span data-stu-id="34d15-101">Specifies the different acknowledgement levels for message delivery.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Full">
      <MemberSignature Language="C#" Value="Full" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement Full = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.DeliveryAcknowledgement.Full" />
      <MemberSignature Language="VB.NET" Value="Full" />
      <MemberSignature Language="F#" Value="Full = 3" Usage="Microsoft.Azure.Devices.DeliveryAcknowledgement.Full" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="34d15-102">Für die Übermittlung erfolgreich war oder fehlgeschlagen ist eine Bestätigung gesendet.</span><span class="sxs-lookup"><span data-stu-id="34d15-102">An acknowledgement is sent on delivery success or failure.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NegativeOnly">
      <MemberSignature Language="C#" Value="NegativeOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement NegativeOnly = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.DeliveryAcknowledgement.NegativeOnly" />
      <MemberSignature Language="VB.NET" Value="NegativeOnly" />
      <MemberSignature Language="F#" Value="NegativeOnly = 1" Usage="Microsoft.Azure.Devices.DeliveryAcknowledgement.NegativeOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="34d15-103">Bestätigung wird gesendet, nur wenn die Zustellung fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="34d15-103">Acknowledgement is sent only if delivery fails.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.DeliveryAcknowledgement.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.Azure.Devices.DeliveryAcknowledgement.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="34d15-104">Bestätigung wird nicht auf die Übermittlung oder Fehler gesendet.</span><span class="sxs-lookup"><span data-stu-id="34d15-104">Acknowledgement is NOT sent on delivery or failure.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PositiveOnly">
      <MemberSignature Language="C#" Value="PositiveOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement PositiveOnly = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.DeliveryAcknowledgement.PositiveOnly" />
      <MemberSignature Language="VB.NET" Value="PositiveOnly" />
      <MemberSignature Language="F#" Value="PositiveOnly = 2" Usage="Microsoft.Azure.Devices.DeliveryAcknowledgement.PositiveOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="34d15-105">Bestätigung wird nur auf Übermittlung erfolgreich gesendet.</span><span class="sxs-lookup"><span data-stu-id="34d15-105">Acknowledgement is sent only on delivery succeeds.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>