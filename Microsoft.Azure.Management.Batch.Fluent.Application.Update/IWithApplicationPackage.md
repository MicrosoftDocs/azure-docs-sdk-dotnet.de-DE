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
            Die Phase der Erstellung eines Anwendungspakets Update mithilfe der Anwendung eine Batchverarbeitung.
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
        <param name="version">Die Version der Anwendung.</param>
        <summary>
            Erste Stufe neuen Anwendungspakets in Batch-Konto-Anwendung erstellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>nächste Stufe auf die Anwendung zu erstellen.</return>
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
        <param name="version">Die Verweis-Version der Anwendung entfernt werden soll.</param>
        <summary>
            Löscht den angegebenen Anwendungspaket aus der Anwendung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die Phase, die aktualisierbare Batch-Konto-Definition darstellt.</return>
      </Docs>
    </Member>
  </Members>
</Type>