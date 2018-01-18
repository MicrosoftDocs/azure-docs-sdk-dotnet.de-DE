<Type Name="DisableJobOption" FullName="Microsoft.Azure.Batch.Common.DisableJobOption">
  <TypeSignature Language="C#" Value="public enum DisableJobOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DisableJobOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.DisableJobOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum DisableJobOption" />
  <TypeSignature Language="F#" Value="type DisableJobOption = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="ad15d-101">Gibt an, was mit aktiven Aufgaben während ein Auftrag deaktivierungsvorgangs zu tun.</span><span class="sxs-lookup"><span data-stu-id="ad15d-101">Specifies what to do with active tasks during a disable job operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableJobOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableJobOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.DisableJobOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableJobOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad15d-102">Beenden Sie derzeit ausgeführte Tasks, und sie requeue.</span><span class="sxs-lookup"><span data-stu-id="ad15d-102">Terminate running tasks and requeue them.</span></span> <span data-ttu-id="ad15d-103">Die Tasks werden erneut ausgeführt, sobald der Auftrag aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ad15d-103">The tasks will run again when the job is enabled.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableJobOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableJobOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.DisableJobOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableJobOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad15d-104">Ausführen von Aufgaben zu beenden.</span><span class="sxs-lookup"><span data-stu-id="ad15d-104">Terminate running tasks.</span></span> <span data-ttu-id="ad15d-105">Die Tasks werden nicht erneut ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ad15d-105">The tasks will not run again.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Wait">
      <MemberSignature Language="C#" Value="Wait" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableJobOption Wait = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableJobOption.Wait" />
      <MemberSignature Language="VB.NET" Value="Wait" />
      <MemberSignature Language="F#" Value="Wait = 2" Usage="Microsoft.Azure.Batch.Common.DisableJobOption.Wait" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableJobOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad15d-106">Ermöglichen Sie die derzeit ausgeführten Tasks ab.</span><span class="sxs-lookup"><span data-stu-id="ad15d-106">Allow currently running tasks to complete.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>