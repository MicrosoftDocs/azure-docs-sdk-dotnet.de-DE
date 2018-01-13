<Type Name="IWithSourceControl&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSourceControl&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSourceControl&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceControl`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSourceControl`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceControl(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithSourceControl&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT">Der Typ der Ressource.</typeparam>
    <summary>
            Die Definition für eine Web-app bereitstellen, ermöglichen, dass Datenquellen-Steuerelement festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSourceControl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;&gt; DefineSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt;&gt; DefineSourceControl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSourceControl`1.DefineSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSourceControl () As IBlank(Of IWithCreate(Of FluentT))" />
      <MemberSignature Language="F#" Value="abstract member DefineSourceControl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;&gt;" Usage="iWithSourceControl.DefineSourceControl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet die Definition eines neuen Datenquellen-Steuerelements an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition eines Datenquellen-Steuerelement.</return>
      </Docs>
    </Member>
    <Member MemberName="WithLocalGitSourceControl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithLocalGitSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithLocalGitSourceControl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSourceControl`1.WithLocalGitSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLocalGitSourceControl () As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithLocalGitSourceControl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSourceControl.WithLocalGitSourceControl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt die Datenquellen-Steuerelements zu einem lokalen Git-Repository für die Web-app an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>