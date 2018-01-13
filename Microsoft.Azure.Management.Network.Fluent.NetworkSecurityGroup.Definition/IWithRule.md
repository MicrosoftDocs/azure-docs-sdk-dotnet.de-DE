<Type Name="IWithRule" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithRule">
  <TypeSignature Language="C#" Value="public interface IWithRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRule" />
  <TypeSignature Language="F#" Value="type IWithRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e2090-101">Die Stufe festlegen, dass eine neue Sicherheitsregel definieren.</span><span class="sxs-lookup"><span data-stu-id="e2090-101">The stage allowing to define a new security rule.</span></span>
            <span data-ttu-id="e2090-102">Wenn die Beschreibung der Sicherheitsregel genug abgeschlossen ist, verwenden Sie Attachable.attach() für die Verbindung zu dieser Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="e2090-102">When the security rule description is complete enough, use  Attachable.attach() to attach it to this network security group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithCreate&gt; DefineRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithCreate&gt; DefineRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithRule.DefineRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRule (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithCreate&gt;" Usage="iWithRule.DefineRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e2090-103">Der Name für die neue Sicherheitsregel.</span><span class="sxs-lookup"><span data-stu-id="e2090-103">The name for the new security rule.</span></span></param>
        <summary>
            <span data-ttu-id="e2090-104">Startet die Definition einer neuen Sicherheits-Regel an.</span><span class="sxs-lookup"><span data-stu-id="e2090-104">Starts the definition of a new security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e2090-105">Die erste Phase der Sicherheitsgruppen-Regeldefinition.</span><span class="sxs-lookup"><span data-stu-id="e2090-105">The first stage of the security rule definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>