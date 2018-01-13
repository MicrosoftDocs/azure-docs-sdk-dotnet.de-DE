<Type Name="IWithInboundNatRule" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatRule">
  <TypeSignature Language="C#" Value="public interface IWithInboundNatRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInboundNatRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInboundNatRule" />
  <TypeSignature Language="F#" Value="type IWithInboundNatRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der einen Load Balancer-Definition, die zum Erstellen einer neuen NAT-Eingangsregel ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule&gt; DefineInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule&gt; DefineInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatRule.DefineInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineInboundNatRule (name As String) As IBlank(Of IWithCreateAndInboundNatRule)" />
      <MemberSignature Language="F#" Value="abstract member DefineInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule&gt;" Usage="iWithInboundNatRule.DefineInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der NAT-Eingangsregel.</param>
        <summary>
            Beginn der Definition einer neuen NAT-Eingangsregel zum Lastenausgleich hinzufügen.
            Die Definition muss mit einem Aufruf von LoadBalancerInboundNatRule.DefinitionStages.WithAttach.attach() abgeschlossen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des der neuen Regel für eingehende NAT Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>