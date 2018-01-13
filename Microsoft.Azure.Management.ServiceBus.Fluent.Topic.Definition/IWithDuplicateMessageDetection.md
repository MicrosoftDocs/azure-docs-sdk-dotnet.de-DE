<Type Name="IWithDuplicateMessageDetection" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDuplicateMessageDetection">
  <TypeSignature Language="C#" Value="public interface IWithDuplicateMessageDetection" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDuplicateMessageDetection" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDuplicateMessageDetection" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDuplicateMessageDetection" />
  <TypeSignature Language="F#" Value="type IWithDuplicateMessageDetection = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der themadefinition, sodass Dauer des Verlaufs Erkennung doppelter Nachrichten an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDuplicateMessageDetection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithDuplicateMessageDetection (TimeSpan duplicateDetectionHistoryDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithDuplicateMessageDetection(valuetype System.TimeSpan duplicateDetectionHistoryDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDuplicateMessageDetection.WithDuplicateMessageDetection(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDuplicateMessageDetection (duplicateDetectionHistoryDuration As TimeSpan) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDuplicateMessageDetection : TimeSpan -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate" Usage="iWithDuplicateMessageDetection.WithDuplicateMessageDetection duplicateDetectionHistoryDuration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="duplicateDetectionHistoryDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="duplicateDetectionHistoryDuration">Die Dauer des Verlaufs.</param>
        <summary>
            Gibt die Dauer des Verlaufs Erkennung doppelter Nachrichten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der themadefinition.</return>
      </Docs>
    </Member>
  </Members>
</Type>