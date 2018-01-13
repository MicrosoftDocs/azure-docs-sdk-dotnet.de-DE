<Type Name="IWithSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet">
  <TypeSignature Language="C#" Value="public interface IWithSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet" />
  <TypeSignature Language="F#" Value="type IWithSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der Definition des virtuellen Netzwerks, sodass Subnetze hinzufügen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet&gt; DefineSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet&gt; DefineSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet.DefineSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSubnet (name As String) As IBlank(Of IWithCreateAndSubnet)" />
      <MemberSignature Language="F#" Value="abstract member DefineSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet&gt;" Usage="iWithSubnet.DefineSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Subnetzes.</param>
        <summary>
            Beginn der Definition ein neues Subnetz im virtuellen Netzwerk hinzufügen.
            Die Definition muss mit einem Aufruf von Subnet.DefinitionStages.WithAttach.attach() abgeschlossen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des der neuen subnetzdefinition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithSubnet (string name, string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithSubnet(string name, string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet.WithSubnet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (name As String, cidr As String) As IWithCreateAndSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet" Usage="iWithSubnet.WithSubnet (name, cidr)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name, mit dem Subnetz zuweisen.</param>
        <param name="cidr">Der Adressraum des Subnetzes innerhalb des Adressraums des Netzwerks mithilfe der CIDR-Notation.</param>
        <summary>
            Das virtuelle Netzwerk hinzugefügt explizit ein Subnetz.
            Wenn keine Subnetze explizit angegeben werden, wird eine standardsubnetz aufgerufen, "subnet1" für den gesamten ersten Adressraum erstellt werden.
            Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedes Mal, die es verwendet wird, ein neues Subnetz wird zum Netzwerk hinzugefügt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithSubnets (System.Collections.Generic.IDictionary&lt;string,string&gt; nameCidrPairs);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithSubnets(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; nameCidrPairs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet.WithSubnets(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnets (nameCidrPairs As IDictionary(Of String, String)) As IWithCreateAndSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithSubnets : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet" Usage="iWithSubnet.WithSubnets nameCidrPairs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameCidrPairs" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nameCidrPairs">Eine Zuordnung der CIDR-Adressen für die Subnetze, die indiziert werden, durch den Namen aller Subnetze definiert werden.</param>
        <summary>
            Explizit definiert Subnetze im virtuellen Netzwerk basierend auf der bereitgestellten Zuordnung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>