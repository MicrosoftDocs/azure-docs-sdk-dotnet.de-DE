<Type Name="IWithMessageLockDuration" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageLockDuration">
  <TypeSignature Language="C#" Value="public interface IWithMessageLockDuration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageLockDuration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageLockDuration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageLockDuration" />
  <TypeSignature Language="F#" Value="type IWithMessageLockDuration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="31c9e-101">Die Stufe der die Warteschlangendefinition, sodass Dauer für eine nachrichtensperre zu definieren.</span><span class="sxs-lookup"><span data-stu-id="31c9e-101">The stage of the queue definition allowing to define duration for message lock.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageLockDurationInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithMessageLockDurationInSeconds (int durationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithMessageLockDurationInSeconds(int32 durationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageLockDuration.WithMessageLockDurationInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageLockDurationInSeconds (durationInSeconds As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageLockDurationInSeconds : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithMessageLockDuration.WithMessageLockDurationInSeconds durationInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="durationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="durationInSeconds"><span data-ttu-id="31c9e-102">Die Dauer der Sperre in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="31c9e-102">Duration of a lock in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="31c9e-103">Gibt die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="31c9e-103">Specifies the amount of time that the message is locked for other receivers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="31c9e-104">Die nächste Phase der Warteschlange aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="31c9e-104">The next stage of queue update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>