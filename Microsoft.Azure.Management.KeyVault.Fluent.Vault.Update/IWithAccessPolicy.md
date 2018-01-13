<Type Name="IWithAccessPolicy" FullName="Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy">
  <TypeSignature Language="C#" Value="public interface IWithAccessPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAccessPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAccessPolicy" />
  <TypeSignature Language="F#" Value="type IWithAccessPolicy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Ein schlüsseltresors aktualisieren, sodass Zugriffsrichtlinien geändert, angefügt oder entfernt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt; DefineAccessPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt; DefineAccessPolicy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy.DefineAccessPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAccessPolicy () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAccessPolicy : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt;" Usage="iWithAccessPolicy.DefineAccessPolicy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet die Definition einer neuen Richtlinie für den Zugriff auf diesen schlüsseltresor hinzugefügt werden.
            </summary>
        <returns>die erste Phase der Richtliniendefinition Zugriff</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate UpdateAccessPolicy (string objectId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate UpdateAccessPolicy(string objectId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy.UpdateAccessPolicy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAccessPolicy (objectId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateAccessPolicy : string -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithAccessPolicy.UpdateAccessPolicy objectId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="objectId">ObjectId der Objekt-ID des Active Directory-Identität der Zugriffsrichtlinie gilt für</param>
        <summary>
            Startet das Update von einer vorhandenen Richtlinie für den Zugriff auf diesen schlüsseltresor angefügt.
            </summary>
        <returns>der Update-Phase der Richtliniendefinition Zugriff</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate WithAccessPolicy (Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy accessPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate WithAccessPolicy(class Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy accessPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy.WithAccessPolicy(Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAccessPolicy (accessPolicy As IAccessPolicy) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAccessPolicy : Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate" Usage="iWithAccessPolicy.WithAccessPolicy accessPolicy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessPolicy" Type="Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy" />
      </Parameters>
      <Docs>
        <param name="accessPolicy">AccessPolicy der vorhandenen Zugriffsrichtlinie</param>
        <summary>
            Fügen Sie einer vorhandenen Zugriffsrichtlinie.
            </summary>
        <returns>die schlüsseltresor-Update-Phase</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate WithoutAccessPolicy (string objectId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate WithoutAccessPolicy(string objectId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy.WithoutAccessPolicy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAccessPolicy (objectId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAccessPolicy : string -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate" Usage="iWithAccessPolicy.WithoutAccessPolicy objectId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="objectId">ObjectId der Objekt-ID des Active Directory-Identität der Zugriffsrichtlinie gilt für</param>
        <summary>
            Entfernen Sie eine Zugriffsrichtlinie aus der Zugriffsliste der Richtlinie ein.
            </summary>
        <returns>die schlüsseltresor-Update-Phase</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>