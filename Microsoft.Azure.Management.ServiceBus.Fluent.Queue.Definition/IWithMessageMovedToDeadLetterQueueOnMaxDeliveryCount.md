<Type Name="IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount">
  <TypeSignature Language="C#" Value="public interface IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="F#" Value="type IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der die Warteschlangendefinition an maximale Übermittlungsanzahl Nachricht vor dem Verschieben an Dead Letter-Warteschlange zulassen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount (int deliveryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount(int32 deliveryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount.WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount (deliveryCount As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount.WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount deliveryCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deliveryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deliveryCount">Maximale Übermittlungsanzahl.</param>
        <summary>
            Gibt die maximale Anzahl der Häufigkeit, mit die eine Nachricht übermittelt werden kann. Sobald diese Anzahl überschritten wurde, werden Nachrichten an die Dead Letter-Warteschlange verschoben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Warteschlangendefinition.</return>
      </Docs>
    </Member>
  </Members>
</Type>