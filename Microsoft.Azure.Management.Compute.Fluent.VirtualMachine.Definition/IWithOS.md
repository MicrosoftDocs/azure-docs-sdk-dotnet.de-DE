<Type Name="IWithOS" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS">
  <TypeSignature Language="C#" Value="public interface IWithOS" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOS" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOS" />
  <TypeSignature Language="F#" Value="type IWithOS = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computers, ermöglicht das Betriebssystemabbild angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLatestLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithLatestLinuxImage (string publisher, string offer, string sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithLatestLinuxImage(string publisher, string offer, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithLatestLinuxImage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestLinuxImage (publisher As String, offer As String, sku As String) As IWithLinuxRootUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithLatestLinuxImage : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithLatestLinuxImage (publisher, offer, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">Gibt den Herausgeber eines Bilds.</param>
        <param name="offer">Gibt ein Angebot des Images an.</param>
        <param name="sku">Gibt eine SKU des Images an.</param>
        <summary>
            Gibt an, dass die neueste Version von einem Marketplace-Linux-Image als Betriebssystem des virtuellen Computers verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithLatestWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithLatestWindowsImage (string publisher, string offer, string sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithLatestWindowsImage(string publisher, string offer, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithLatestWindowsImage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLatestWindowsImage (publisher As String, offer As String, sku As String) As IWithWindowsAdminUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithLatestWindowsImage : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithLatestWindowsImage (publisher, offer, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
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
            Gibt an, dass die neueste Version von einem Marketplace-Image für Windows als Betriebssystem des virtuellen Computers verwendet werden sollten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManaged WithLinuxCustomImage (string customImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManaged WithLinuxCustomImage(string customImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithLinuxCustomImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxCustomImage (customImageId As String) As IWithLinuxRootUsernameManaged" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxCustomImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManaged" Usage="iWithOS.WithLinuxCustomImage customImageId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customImageId">Die Ressourcen-ID eines benutzerdefinierten Bilds.</param>
        <summary>
            Gibt die Ressourcen-ID eines benutzerdefinierten Bilds Linux als Betriebssystem der virtuellen Maschine verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPopularLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithPopularLinuxImage (Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage knownImage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithPopularLinuxImage(valuetype Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage knownImage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithPopularLinuxImage(Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPopularLinuxImage (knownImage As KnownLinuxVirtualMachineImage) As IWithLinuxRootUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithPopularLinuxImage : Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithPopularLinuxImage knownImage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="knownImage" Type="Microsoft.Azure.Management.Compute.Fluent.KnownLinuxVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="knownImage">Eine bekannte Marketplace-Image.</param>
        <summary>
            Gibt ein bekanntes Marketplace-Linux-Image für das Betriebssystem des virtuellen Computers verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPopularWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithPopularWindowsImage (Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage knownImage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithPopularWindowsImage(valuetype Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage knownImage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithPopularWindowsImage(Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPopularWindowsImage (knownImage As KnownWindowsVirtualMachineImage) As IWithWindowsAdminUsernameManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithPopularWindowsImage : Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithPopularWindowsImage knownImage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="knownImage" Type="Microsoft.Azure.Management.Compute.Fluent.KnownWindowsVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="knownImage">Eine bekannte Marketplace-Image.</param>
        <summary>
            Gibt ein bekanntes Marketplace-Windows-Image für das Betriebssystem des virtuellen Computers verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecializedOSDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithSpecializedOSDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithSpecializedOSDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithSpecializedOSDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSpecializedOSDisk (disk As IDisk, osType As OperatingSystemTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSpecializedOSDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithOS.WithSpecializedOSDisk (disk, osType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" />
      </Parameters>
      <Docs>
        <param name="disk">Die verwaltete Datenträger anfügen.</param>
        <param name="osType">Der Betriebssystemtyp.</param>
        <summary>
            Gibt einen verwalteten spezielle Betriebssystem-Datenträger an den virtuellen Computer angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecializedOSUnmanagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithSpecializedOSUnmanagedDisk (string osDiskUrl, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithSpecializedOSUnmanagedDisk(string osDiskUrl, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithSpecializedOSUnmanagedDisk(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSpecializedOSUnmanagedDisk (osDiskUrl As String, osType As OperatingSystemTypes) As IWithUnmanagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSpecializedOSUnmanagedDisk : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate" Usage="iWithOS.WithSpecializedOSUnmanagedDisk (osDiskUrl, osType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="osDiskUrl" Type="System.String" />
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" />
      </Parameters>
      <Docs>
        <param name="osDiskUrl">Die URL für das Betriebssystem den OsDiskUrl Datenträger in Azure Storage-Kontos.</param>
        <param name="osType">Der Betriebssystemtyp.</param>
        <summary>
            Gibt einen nicht verwalteten spezielle Betriebssystem-Datenträger an den virtuellen Computer angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecificLinuxImageVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithSpecificLinuxImageVersion (Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged WithSpecificLinuxImageVersion(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithSpecificLinuxImageVersion(Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference)" />
      <MemberSignature Language="F#" Value="abstract member WithSpecificLinuxImageVersion : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" Usage="iWithOS.WithSpecificLinuxImageVersion imageReference" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" />
      </Parameters>
      <Docs>
        <param name="imageReference">Beschreibt, Verleger, Angebot, SKU und Version des Abbilds direkten Zugang zum Markt.</param>
        <summary>
            Gibt eine Version des direkten Zugang zum Markt-Linux-Image als Betriebssystem des virtuellen Computers verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSpecificWindowsImageVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithSpecificWindowsImageVersion (Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged WithSpecificWindowsImageVersion(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference imageReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithSpecificWindowsImageVersion(Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference)" />
      <MemberSignature Language="F#" Value="abstract member WithSpecificWindowsImageVersion : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" Usage="iWithOS.WithSpecificWindowsImageVersion imageReference" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" />
      </Parameters>
      <Docs>
        <param name="imageReference">Beschreibt, Verleger, Angebot, SKU und Version des Abbilds direkten Zugang zum Markt.</param>
        <summary>
            Gibt eine Version der Marketplace-Windows-Abbild als Betriebssystem des virtuellen Computers verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithStoredLinuxImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameUnmanaged WithStoredLinuxImage (string imageUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameUnmanaged WithStoredLinuxImage(string imageUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithStoredLinuxImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStoredLinuxImage (imageUrl As String) As IWithLinuxRootUsernameUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithStoredLinuxImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameUnmanaged" Usage="iWithOS.WithStoredLinuxImage imageUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageUrl">Die URL einer virtuellen Festplatte.</param>
        <summary>
            Gibt ein Benutzer (generalisiert) Linux-Image für das Betriebssystem des virtuellen Computers verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithStoredWindowsImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameUnmanaged WithStoredWindowsImage (string imageUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameUnmanaged WithStoredWindowsImage(string imageUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithStoredWindowsImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStoredWindowsImage (imageUrl As String) As IWithWindowsAdminUsernameUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithStoredWindowsImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameUnmanaged" Usage="iWithOS.WithStoredWindowsImage imageUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageUrl">Die URL einer virtuellen Festplatte.</param>
        <summary>
            Gibt an, die Benutzer (generalisiert) Windows-Image für das Betriebssystem des virtuellen Computers verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManaged WithWindowsCustomImage (string customImageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManaged WithWindowsCustomImage(string customImageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS.WithWindowsCustomImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsCustomImage (customImageId As String) As IWithWindowsAdminUsernameManaged" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsCustomImage : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManaged" Usage="iWithOS.WithWindowsCustomImage customImageId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customImageId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customImageId">Die Ressourcen-ID des benutzerdefinierten Images.</param>
        <summary>
            Gibt die Ressourcen-ID eines benutzerdefinierten Bilds Windows als Betriebssystem des virtuellen Computers verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>