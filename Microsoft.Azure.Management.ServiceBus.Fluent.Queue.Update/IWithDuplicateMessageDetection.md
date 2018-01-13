<Type Name="IWithDuplicateMessageDetection" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithDuplicateMessageDetection">
  <TypeSignature Language="C#" Value="public interface IWithDuplicateMessageDetection" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDuplicateMessageDetection" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithDuplicateMessageDetection" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDuplicateMessageDetection" />
  <TypeSignature Language="F#" Value="type IWithDuplicateMessageDetection = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der die Warteschlangendefinition an die Dauer des Verlaufs Erkennung doppelter Nachrichten ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDuplicateMessageDetectionHistoryDuration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithDuplicateMessageDetectionHistoryDuration (TimeSpan duration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithDuplicateMessageDetectionHistoryDuration(valuetype System.TimeSpan duration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithDuplicateMessageDetection.WithDuplicateMessageDetectionHistoryDuration(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDuplicateMessageDetectionHistoryDuration (duration As TimeSpan) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDuplicateMessageDetectionHistoryDuration : TimeSpan -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithDuplicateMessageDetection.WithDuplicateMessageDetectionHistoryDuration duration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="duration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="duration">Die Dauer des Verlaufs.</param>
        <summary>
            Gibt die Dauer des Verlaufs Erkennung doppelter Nachrichten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Warteschlange aktualisieren.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDuplicateMessageDetection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutDuplicateMessageDetection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutDuplicateMessageDetection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithDuplicateMessageDetection.WithoutDuplicateMessageDetection" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDuplicateMessageDetection () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutDuplicateMessageDetection : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithDuplicateMessageDetection.WithoutDuplicateMessageDetection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, die doppelte Nachricht Erkennung deaktiviert werden muss.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Warteschlange aktualisieren.</return>
      </Docs>
    </Member>
  </Members>
</Type>