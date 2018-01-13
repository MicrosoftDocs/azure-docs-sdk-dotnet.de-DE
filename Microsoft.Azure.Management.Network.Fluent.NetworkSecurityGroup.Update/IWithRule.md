<Type Name="IWithRule" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule">
  <TypeSignature Language="C#" Value="public interface IWithRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRule" />
  <TypeSignature Language="F#" Value="type IWithRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Ressourcendefinition hinzufügen oder Entfernen von Sicherheitsregeln ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt; DefineRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt; DefineRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule.DefineRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;" Usage="iWithRule.DefineRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des neuen Sicherheitsregel.</param>
        <summary>
            Beginn der Definition eine neue Sicherheitsregel dieser Netzwerksicherheitsgruppe hinzugefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der neue Sicherheitsgruppen-Regeldefinition.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate UpdateRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate UpdateRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule.UpdateRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithRule.UpdateRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der eine vorhandene Sicherheitsregel.</param>
        <summary>
            Startet die Beschreibung eines Updates für eine vorhandene Sicherheitsregel von dieser Netzwerksicherheitsgruppe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der die Beschreibung der Sicherheitsregel Update.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate WithoutRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate WithoutRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IWithRule.WithoutRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate" Usage="iWithRule.WithoutRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Sicherheitsregel zu entfernen.</param>
        <summary>
            Entfernt eine vorhandene Sicherheitsregel.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Netzwerk-sicherheitsgruppenbeschreibung.</return>
      </Docs>
    </Member>
  </Members>
</Type>