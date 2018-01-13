<Type Name="CloudTaskExtensions" FullName="Microsoft.Azure.Batch.Conventions.Files.CloudTaskExtensions">
  <TypeSignature Language="C#" Value="public static class CloudTaskExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CloudTaskExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.CloudTaskExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CloudTaskExtensions" />
  <TypeSignature Language="F#" Value="type CloudTaskExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="95170-101">Stellt Methoden zum Arbeiten mit Ausgaben von einem <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span><span class="sxs-lookup"><span data-stu-id="95170-101">Provides methods for working with the outputs of a <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OutputStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage OutputStorage (this Microsoft.Azure.Batch.CloudTask task, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage OutputStorage(class Microsoft.Azure.Batch.CloudTask task, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudTaskExtensions.OutputStorage(Microsoft.Azure.Batch.CloudTask,Microsoft.WindowsAzure.Storage.CloudStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function OutputStorage (task As CloudTask, storageAccount As CloudStorageAccount) As TaskOutputStorage" />
      <MemberSignature Language="F#" Value="static member OutputStorage : Microsoft.Azure.Batch.CloudTask * Microsoft.WindowsAzure.Storage.CloudStorageAccount -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudTaskExtensions.OutputStorage (task, storageAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="task" Type="Microsoft.Azure.Batch.CloudTask" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
      </Parameters>
      <Docs>
        <param name="task"><span data-ttu-id="95170-102">Der Task für die Ausgabe-Speicher abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="95170-102">The task for which to get output storage.</span></span></param>
        <param name="storageAccount"><span data-ttu-id="95170-103">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="95170-103">The storage account linked to the Azure Batch account.</span></span></param>
        <summary>
            <span data-ttu-id="95170-104">Ruft die <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" /> für einen angegebenen <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span><span class="sxs-lookup"><span data-stu-id="95170-104">Gets the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" /> for a specified <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="95170-105">Eine TaskOutputStorage für den angegebenen Vorgang.</span><span class="sxs-lookup"><span data-stu-id="95170-105">A TaskOutputStorage for the specified task.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>