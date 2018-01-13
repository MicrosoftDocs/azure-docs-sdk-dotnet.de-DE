<Type Name="IWithStorageAccount" FullName="Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithStorageAccount">
  <TypeSignature Language="C#" Value="public interface IWithStorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStorageAccount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStorageAccount" />
  <TypeSignature Language="F#" Value="type IWithStorageAccount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Ein app-Funktionsdefinition, sodass Speicherkonto angegeben werden.
            Ein Speicherkonto ist erforderlich zum Speichern von Funktion ausführungslaufzeit, Trigger und Protokolle.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithExistingStorageAccount (Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithExistingStorageAccount(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithStorageAccount.WithExistingStorageAccount(Microsoft.Azure.Management.Storage.Fluent.IStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingStorageAccount (storageAccount As IStorageAccount) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingStorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithStorageAccount.WithExistingStorageAccount storageAccount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
      </Parameters>
      <Docs>
        <param name="storageAccount">Das zu verwendende Speicherkonto.</param>
        <summary>
            Gibt das Speicherkonto für die Funktion-app verwenden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewStorageAccount (string name, Microsoft.Azure.Management.Storage.Fluent.Models.SkuName sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithNewStorageAccount(string name, valuetype Microsoft.Azure.Management.Storage.Fluent.Models.SkuName sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithStorageAccount.WithNewStorageAccount(System.String,Microsoft.Azure.Management.Storage.Fluent.Models.SkuName)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (name As String, sku As SkuName) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : string * Microsoft.Azure.Management.Storage.Fluent.Models.SkuName -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithStorageAccount.WithNewStorageAccount (name, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Fluent.Models.SkuName" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Speicherkontos.</param>
        <param name="sku">Die Sku des Speicherkontos.</param>
        <summary>
            Erstellt ein neues Speicherkonto für die Funktion-app verwenden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>