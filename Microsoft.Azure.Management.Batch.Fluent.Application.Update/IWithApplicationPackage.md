<Type Name="IWithApplicationPackage" FullName="Microsoft.Azure.Management.Batch.Fluent.Application.Update.IWithApplicationPackage">
  <TypeSignature Language="C#" Value="public interface IWithApplicationPackage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithApplicationPackage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Application.Update.IWithApplicationPackage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithApplicationPackage" />
  <TypeSignature Language="F#" Value="type IWithApplicationPackage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="16a9e-101">Die Phase der Erstellung eines Anwendungspakets Update mithilfe der Anwendung eine Batchverarbeitung.</span><span class="sxs-lookup"><span data-stu-id="16a9e-101">The stage of a Batch application update allowing the creation of an application package.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewApplicationPackage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate DefineNewApplicationPackage (string version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate DefineNewApplicationPackage(string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.Update.IWithApplicationPackage.DefineNewApplicationPackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewApplicationPackage (version As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DefineNewApplicationPackage : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate" Usage="iWithApplicationPackage.DefineNewApplicationPackage version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="16a9e-102">Die Version der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="16a9e-102">The version of the application.</span></span></param>
        <summary>
            <span data-ttu-id="16a9e-103">Erste Stufe neuen Anwendungspakets in Batch-Konto-Anwendung erstellt.</span><span class="sxs-lookup"><span data-stu-id="16a9e-103">First stage to create new application package in Batch account application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="16a9e-104">nächste Stufe auf die Anwendung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="16a9e-104">Next stage to create the application.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutApplicationPackage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate WithoutApplicationPackage (string version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate WithoutApplicationPackage(string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.Update.IWithApplicationPackage.WithoutApplicationPackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutApplicationPackage (version As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutApplicationPackage : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate" Usage="iWithApplicationPackage.WithoutApplicationPackage version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="16a9e-105">Die Verweis-Version der Anwendung entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="16a9e-105">The reference version of the application to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="16a9e-106">Löscht den angegebenen Anwendungspaket aus der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="16a9e-106">Deletes specified application package from the application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="16a9e-107">die Phase, die aktualisierbare Batch-Konto-Definition darstellt.</span><span class="sxs-lookup"><span data-stu-id="16a9e-107">The stage representing updatable batch account definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>