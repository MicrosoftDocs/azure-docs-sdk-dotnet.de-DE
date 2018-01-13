<Type Name="IWithInboundNatPool" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatPool">
  <TypeSignature Language="C#" Value="public interface IWithInboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInboundNatPool" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInboundNatPool" />
  <TypeSignature Language="F#" Value="type IWithInboundNatPool = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der eine Load Balancer-Definition, die zum Erstellen eines neuen eingehenden NAT-Anwendungspools für eine VM-Skalierungsgruppe zulassen festgelegt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineInboundNatPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool&gt; DefineInboundNatPool (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool&gt; DefineInboundNatPool(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatPool.DefineInboundNatPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineInboundNatPool (name As String) As IBlank(Of IWithCreateAndInboundNatPool)" />
      <MemberSignature Language="F#" Value="abstract member DefineInboundNatPool : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool&gt;" Usage="iWithInboundNatPool.DefineInboundNatPool name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der eingehenden NAT-Pool.</param>
        <summary>
            Beginn der Definition einer neuen Inbount NAT-Pool zum Lastenausgleich hinzufügen.
            Die Definition muss mit einem Aufruf von LoadBalancerInboundNatPool.DefinitionStages.WithAttach.attach() abgeschlossen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der neue eingehende NAT-Pool-Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>