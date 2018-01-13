<Type Name="IWithSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet">
  <TypeSignature Language="C#" Value="public interface IWithSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet" />
  <TypeSignature Language="F#" Value="type IWithSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase des virtuellen Netzwerks aktualisieren zum Hinzufügen oder entfernen Sie die Subnetze ermöglichen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt; DefineSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt; DefineSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.DefineSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSubnet (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt;" Usage="iWithSubnet.DefineSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des neuen Subnetzes.</param>
        <summary>
            Beginn der Definition eines neuen Teilnetzes mit diesem virtuellen Netzwerk hinzugefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des der neuen subnetzdefinition.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate UpdateSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate UpdateSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.UpdateSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSubnet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithSubnet.UpdateSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name von einem vorhandenen Subnetz.</param>
        <summary>
            Startet die Beschreibung eines Updates von einem vorhandenen Subnetz des Netzwerks an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Stufe der die Beschreibung des Subnetzes.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithoutSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithoutSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.WithoutSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSubnet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithSubnet.WithoutSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Subnetzes, zu entfernen.</param>
        <summary>
            Entfernt ein Subnetz aus dem virtuellen Netzwerk an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des virtuellen Netzwerks Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnet (string name, string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnet(string name, string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.WithSubnet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (name As String, cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithSubnet.WithSubnet (name, cidr)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
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
            Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedes Mal, die es verwendet wird, ein neues Subnetz wird zum Netzwerk hinzugefügt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des virtuellen Netzwerks Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnets (System.Collections.Generic.IDictionary&lt;string,string&gt; nameCidrPairs);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnets(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; nameCidrPairs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.WithSubnets(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnets (nameCidrPairs As IDictionary(Of String, String)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnets : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithSubnet.WithSubnets nameCidrPairs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameCidrPairs" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nameCidrPairs">Eine Zuordnung der CIDR-Adressen für die Subnetze, die indiziert werden, durch den Namen aller Subnetze hinzugefügt werden.</param>
        <summary>
            Explizit definiert alle Subnetze im virtuellen Netzwerk basierend auf der bereitgestellten Zuordnung.
            Dies ersetzt keine zuvor vorhandenen Subnetze.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des virtuellen Netzwerks Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>