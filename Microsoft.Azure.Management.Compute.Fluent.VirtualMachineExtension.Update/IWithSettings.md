<Type Name="IWithSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithSettings">
  <TypeSignature Language="C#" Value="public interface IWithSettings" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSettings" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithSettings" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSettings" />
  <TypeSignature Language="F#" Value="type IWithSettings = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Erweiterung des virtuellen Computers aktualisieren, hinzufügen oder Aktualisieren von öffentlichen und privaten Einstellungen zulassen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithProtectedSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithProtectedSetting (string key, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithProtectedSetting(string key, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithSettings.WithProtectedSetting(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProtectedSetting (key As String, value As Object) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithProtectedSetting : string * obj -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithSettings.WithProtectedSetting (key, value)" />
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
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key">Der Schlüssel eines Eintrags private-Einstellungen.</param>
        <param name="value">Der Wert des Eintrags private-Einstellungen.</param>
        <summary>
            Gibt einen Eintrag für die private-Einstellungen an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithProtectedSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithProtectedSettings (System.Collections.Generic.IDictionary&lt;string,object&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithProtectedSettings(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithSettings.WithProtectedSettings(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProtectedSettings (settings As IDictionary(Of String, Object)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithProtectedSettings : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithSettings.WithProtectedSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="settings">Die Einstellungen für privaten.</param>
        <summary>
            Gibt Einstellungen für private an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithPublicSetting (string key, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithPublicSetting(string key, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithSettings.WithPublicSetting(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicSetting (key As String, value As Object) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPublicSetting : string * obj -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithSettings.WithPublicSetting (key, value)" />
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
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key">Der Schlüssel eines Eintrags public-Einstellungen.</param>
        <param name="value">Der Wert des Eintrags public-Einstellungen.</param>
        <summary>
            Gibt einen Eintrag für die öffentlichen Einstellungen an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithPublicSettings (System.Collections.Generic.IDictionary&lt;string,object&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithPublicSettings(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithSettings.WithPublicSettings(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicSettings (settings As IDictionary(Of String, Object)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPublicSettings : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithSettings.WithPublicSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="settings">Die öffentlichen Einstellungen.</param>
        <summary>
            Gibt die öffentliche Einstellungen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>