<Type Name="IWithApplication" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication">
  <TypeSignature Language="C#" Value="public interface IWithApplication" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithApplication" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithApplication" />
  <TypeSignature Language="F#" Value="type IWithApplication = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9579f-101">Die Phase der Definition eines Batch-Konto, das der Erstellung einer Batch-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9579f-101">The stage of a Batch account definition allowing the creation of a Batch application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt; DefineNewApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt; DefineNewApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication.DefineNewApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewApplication (applicationId As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt;" Usage="iWithApplication.DefineNewApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId"><span data-ttu-id="9579f-102">Der Verweisname für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9579f-102">The reference name for the application.</span></span></param>
        <summary>
            <span data-ttu-id="9579f-103">Startet eine Definition einer Anwendung in der Batch-Konto erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="9579f-103">Starts a definition of an application to be created in the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9579f-104">Die erste Phase der Definition eines Batch-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9579f-104">The first stage of a Batch application definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate UpdateApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate UpdateApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication.UpdateApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateApplication (applicationId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate" Usage="iWithApplication.UpdateApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId"><span data-ttu-id="9579f-105">Der Verweisname der Anwendung aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="9579f-105">The reference name of the application to be updated.</span></span></param>
        <summary>
            <span data-ttu-id="9579f-106">Startet die Beschreibung des ein Update einer vorhandenen Anwendung von Batches in diesem Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="9579f-106">Begins the description of an update of an existing Batch application in this Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9579f-107">Die erste Phase einer Batchaktualisierung für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9579f-107">The first stage of a Batch application update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutApplication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutApplication (string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutApplication(string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithApplication.WithoutApplication(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutApplication (applicationId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutApplication : string -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithApplication.WithoutApplication applicationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId"><span data-ttu-id="9579f-108">Der Verweisname für die Anwendung entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="9579f-108">The reference name for the application to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="9579f-109">Entfernt die angegebene Anwendung nicht mit dem Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="9579f-109">Removes the specified application from the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9579f-110">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="9579f-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>