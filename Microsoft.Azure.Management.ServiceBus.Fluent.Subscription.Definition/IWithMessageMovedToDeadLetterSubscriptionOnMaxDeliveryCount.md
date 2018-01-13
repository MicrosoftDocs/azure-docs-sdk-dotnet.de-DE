<Type Name="IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount">
  <TypeSignature Language="C#" Value="public interface IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" />
  <TypeSignature Language="F#" Value="type IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Abonnementdefinition ermöglicht maximale Übermittlungsanzahl Nachricht vor dem Verschieben unzustellbare Abonnement angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount (int deliveryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount(int32 deliveryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount.WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount (deliveryCount As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate" Usage="iWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount.WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount deliveryCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deliveryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deliveryCount">Maximale Übermittlungsanzahl.</param>
        <summary>
            Gibt die maximale Anzahl der Häufigkeit, mit die eine Nachricht übermittelt werden kann. Sobald diese Anzahl überschritten wurde, wird Nachricht unzustellbare Abonnement verschoben werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Abonnementdefinition.</return>
      </Docs>
    </Member>
  </Members>
</Type>