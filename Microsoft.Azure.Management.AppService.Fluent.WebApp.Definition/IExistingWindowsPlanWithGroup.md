<Type Name="IExistingWindowsPlanWithGroup" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup">
  <TypeSignature Language="C#" Value="public interface IExistingWindowsPlanWithGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IExistingWindowsPlanWithGroup" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface IExistingWindowsPlanWithGroup" />
  <TypeSignature Language="F#" Value="type IExistingWindowsPlanWithGroup = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Definition einer Web-app ermöglicht Ressourcengruppe angegeben werden, wenn ein neue app Service-Plan ist, erstellt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithExistingResourceGroup (Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup group);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithExistingResourceGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup group) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithExistingResourceGroup(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingResourceGroup (group As IResourceGroup) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithExistingResourceGroup group" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="group" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup" />
      </Parameters>
      <Docs>
        <param name="group">Vorhandene Ressourcengruppe die Ressource in versetzt.</param>
        <summary>
            Ordnet die Ressource eine vorhandene Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithExistingResourceGroup (string groupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithExistingResourceGroup(string groupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithExistingResourceGroup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingResourceGroup (groupName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingResourceGroup : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithExistingResourceGroup groupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="groupName">der Name des zum Platzieren diese Ressource in eine vorhandene Ressourcengruppe.</param>
        <summary>
            Ordnet die Ressource eine vorhandene Ressourcengruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithNewResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewResourceGroup () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithNewResourceGroup " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Fügen Sie die Ressource in eine neue Ressourcengruppe wird erstellt.
            Die Gruppe wird am gleichen Speicherort wie die Ressource erstellt werden.
            Den Namen der Gruppe wird automatisch von den Namen der Ressource abgeleitet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithNewResourceGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewResourceGroup (groupDefinition As ICreatable(Of IResourceGroup)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithNewResourceGroup groupDefinition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupDefinition" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="groupDefinition">Eine erstellbare Definition für eine neue Ressourcengruppe.</param>
        <summary>
            Erstellt eine neue Ressourcengruppe zum Einfügen einer Ressource, basierend auf der Definition angegeben werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithNewResourceGroup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewResourceGroup (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithNewResourceGroup name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der neuen Gruppe.</param>
        <summary>
            Fügen Sie die Ressource in eine neue Ressourcengruppe wird erstellt.
            Die Gruppe wird am gleichen Speicherort wie die Ressource erstellt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>