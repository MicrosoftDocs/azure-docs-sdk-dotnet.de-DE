<Type Name="IWithOS" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS">
  <TypeSignature Language="C#" Value="public interface IWithOS" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOS" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOS" />
  <TypeSignature Language="F#" Value="type IWithOS = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Festlegen des Status von VM-Skalierungsgruppe-Definition ermöglicht das Betriebssystemabbild angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLatestLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithLatestLinuxImage (string publisher, string offer, string sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithLatestLinuxImage(string publisher, string offer, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithLatestLinuxImage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestLinuxImage (publisher As String, offer As String, sku As String) As IWithLinuxRootUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithLatestLinuxImage : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithLatestLinuxImage (publisher, offer, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">Gibt den Herausgeber des Images an.</param>
        <param name="offer">Das Angebot des Images.</param>
        <param name="sku">Die SKU des Images.</param>
        <summary>
            Gibt an, dass die neueste Version von einem Marketplace-Linux-Image verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithLatestWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithLatestWindowsImage (string publisher, string offer, string sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithLatestWindowsImage(string publisher, string offer, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithLatestWindowsImage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestWindowsImage (publisher As String, offer As String, sku As String) As IWithWindowsAdminUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithLatestWindowsImage : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithLatestWindowsImage (publisher, offer, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">Gibt den Herausgeber des Images an.</param>
        <param name="offer">Gibt das Angebot des Images an.</param>
        <param name="sku">Gibt die SKU des Images an.</param>
        <summary>
            Gibt an, dass die neueste Version des angegebenen Marketplace-Windows-Abbilds verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged WithLinuxCustomImage (string customImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged WithLinuxCustomImage(string customImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithLinuxCustomImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxCustomImage (customImageId As String) As IWithLinuxRootUsernameManaged" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxCustomImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged" Usage="iWithOS.WithLinuxCustomImage customImageId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customImageId">Die Ressourcen-ID des benutzerdefinierten Images.</param>
        <summary>
            Gibt die ID eines benutzerdefinierten Bilds Linux verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPopularLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithPopularLinuxImage (Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage knownImage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithPopularLinuxImage(valuetype Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage knownImage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithPopularLinuxImage(Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPopularLinuxImage (knownImage As KnownLinuxVirtualMachineImage) As IWithLinuxRootUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithPopularLinuxImage : Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithPopularLinuxImage knownImage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="knownImage" Type="Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="knownImage">Eine bekannte Marketplace-Image.</param>
        <summary>
            Gibt einen bekannten Marketplace Linux-Image als Betriebssystem des virtuellen Computers verwendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPopularWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithPopularWindowsImage (Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage knownImage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithPopularWindowsImage(valuetype Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage knownImage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithPopularWindowsImage(Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPopularWindowsImage (knownImage As KnownWindowsVirtualMachineImage) As IWithWindowsAdminUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithPopularWindowsImage : Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithPopularWindowsImage knownImage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="knownImage" Type="Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="knownImage">Eine bekannte Marketplace-Image.</param>
        <summary>
            Gibt an einem bekannten Marketplace-Windows-Image als Betriebssystem für die virtuellen Computer in der Menge der Skala verwendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecificLinuxImageVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithSpecificLinuxImageVersion (Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithSpecificLinuxImageVersion(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithSpecificLinuxImageVersion(Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference)" />
      <MemberSignature Language="F#" Value="abstract member WithSpecificLinuxImageVersion : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithSpecificLinuxImageVersion imageReference" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" />
      </Parameters>
      <Docs>
        <param name="imageReference">Beschreibt, Verleger, Angebot, SKU und Version des Abbilds direkten Zugang zum Markt.</param>
        <summary>
            Gibt die spezifische Version einer direkten Zugang zum Markt Linux-Image, das verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecificWindowsImageVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithSpecificWindowsImageVersion (Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithSpecificWindowsImageVersion(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithSpecificWindowsImageVersion(Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference)" />
      <MemberSignature Language="F#" Value="abstract member WithSpecificWindowsImageVersion : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithSpecificWindowsImageVersion imageReference" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" />
      </Parameters>
      <Docs>
        <param name="imageReference">Beschreibt, Verleger, Angebot, SKU und Version der Marketplace-Image.</param>
        <summary>
            Gibt die spezifische Version einer Marketplace benötigten Windows-Abbilds verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithStoredLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged WithStoredLinuxImage (string imageUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged WithStoredLinuxImage(string imageUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithStoredLinuxImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStoredLinuxImage (imageUrl As String) As IWithLinuxRootUsernameUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithStoredLinuxImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged" Usage="iWithOS.WithStoredLinuxImage imageUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageUrl">Die URL der der virtuellen Festplatte.</param>
        <summary>
            Gibt den Benutzer (benutzerdefinierte) Linux Bild als Betriebssystem des virtuellen Computers verwendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithStoredWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged WithStoredWindowsImage (string imageUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged WithStoredWindowsImage(string imageUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithStoredWindowsImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStoredWindowsImage (imageUrl As String) As IWithWindowsAdminUsernameUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithStoredWindowsImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged" Usage="iWithOS.WithStoredWindowsImage imageUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageUrl">Die URL der virtuellen Festplatte.</param>
        <summary>
            Gibt an, die Benutzer (Benutzerdefiniert) Windows-Abbild als Betriebssystem für die virtuellen Computer in der Menge der Skala verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged WithWindowsCustomImage (string customImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged WithWindowsCustomImage(string customImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS.WithWindowsCustomImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsCustomImage (customImageId As String) As IWithWindowsAdminUsernameManaged" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsCustomImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged" Usage="iWithOS.WithWindowsCustomImage customImageId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customImageId">Die Ressourcen-ID des benutzerdefinierten Images.</param>
        <summary>
            Gibt die ID eines benutzerdefinierten Bilds Windows verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>