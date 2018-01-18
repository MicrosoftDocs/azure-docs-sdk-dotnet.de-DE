<Type Name="IWithMessageLockDuration" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageLockDuration">
  <TypeSignature Language="C#" Value="public interface IWithMessageLockDuration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageLockDuration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageLockDuration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageLockDuration" />
  <TypeSignature Language="F#" Value="type IWithMessageLockDuration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ad100-101">Die Phase der Abonnementdefinition, sodass Dauer für eine nachrichtensperre zu definieren.</span><span class="sxs-lookup"><span data-stu-id="ad100-101">The stage of the subscription definition allowing to define duration for message lock.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageLockDurationInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageLockDurationInSeconds (int durationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageLockDurationInSeconds(int32 durationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageLockDuration.WithMessageLockDurationInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageLockDurationInSeconds (durationInSeconds As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageLockDurationInSeconds : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate" Usage="iWithMessageLockDuration.WithMessageLockDurationInSeconds durationInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="durationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="durationInSeconds"><span data-ttu-id="ad100-102">Die Dauer der Sperre in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="ad100-102">Duration of a lock in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="ad100-103">Gibt die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="ad100-103">Specifies the amount of time that the message is locked for other receivers.</span></span>
            <span data-ttu-id="ad100-104">Hinweis: es sei denn, sie explizit außer Kraft gesetzt wird die sperrenstandarddauer beträgt 60 Sekunden an, der maximal zulässige Wert beträgt 300 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="ad100-104">Note: unless it is explicitly overridden the default lock duration is 60 seconds, the maximum allowed value is 300 seconds.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ad100-105">Die nächste Phase der Abonnementdefinition.</span><span class="sxs-lookup"><span data-stu-id="ad100-105">The next stage of subscription definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>