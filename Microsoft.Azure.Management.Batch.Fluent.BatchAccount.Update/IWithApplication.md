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
            Die Phase der Definition eines Batch-Konto, das der Erstellung einer Batch-Anwendung.
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
        <param name="applicationId">Der Verweisname für die Anwendung.</param>
        <summary>
            Startet eine Definition einer Anwendung in der Batch-Konto erstellt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition eines Batch-Anwendung.</return>
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
        <param name="applicationId">Der Verweisname der Anwendung aktualisiert werden.</param>
        <summary>
            Startet die Beschreibung des ein Update einer vorhandenen Anwendung von Batches in diesem Batch-Konto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase einer Batchaktualisierung für die Anwendung.</return>
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
        <param name="applicationId">Der Verweisname für die Anwendung entfernt werden soll.</param>
        <summary>
            Entfernt die angegebene Anwendung nicht mit dem Batch-Konto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>