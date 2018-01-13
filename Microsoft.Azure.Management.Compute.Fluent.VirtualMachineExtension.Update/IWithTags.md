<Type Name="IWithTags" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags">
  <TypeSignature Language="C#" Value="public interface IWithTags" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTags" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTags" />
  <TypeSignature Language="F#" Value="type IWithTags = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Erweiterung des virtuellen Computers aktualisieren, hinzufügen oder Aktualisieren von RFID-Transponder zulassen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutTag">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithoutTag (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithoutTag(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags.WithoutTag(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTag (key As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutTag : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithTags.WithoutTag key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Der Schlüssel des Tags zu entfernen.</param>
        <summary>
            Entfernt ein Tag aus Erweiterung des virtuellen Computers an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithTag">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags.WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTag (key As String, value As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTag : string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithTags.WithTag (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Der Schlüssel für das Tag.</param>
        <param name="value">Der Wert für das Tag.</param>
        <summary>
            Erweiterung des virtuellen Computers hinzugefügt ein-Tag.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithTags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTags (tags As IDictionary(Of String, String)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTags : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithTags.WithTags tags" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags">Tags, die nach Namen indiziert.</param>
        <summary>
            Gibt Tags für die Erweiterung des virtuellen Computers an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>