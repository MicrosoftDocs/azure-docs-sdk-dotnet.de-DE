<Type Name="JobOutputKind" FullName="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind">
  <TypeSignature Language="C#" Value="public sealed class JobOutputKind : IEquatable&lt;Microsoft.Azure.Batch.Conventions.Files.JobOutputKind&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit JobOutputKind extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class JobOutputKind&#xA;Implements IEquatable(Of JobOutputKind)" />
  <TypeSignature Language="F#" Value="type JobOutputKind = class&#xA;    interface IEquatable&lt;JobOutputKind&gt;&#xA;    interface IOutputKind" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Batch.Conventions.Files.JobOutputKind&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="9d816-101">Stellt eine Kategorie von auftragsausgaben, z. B. die Hauptauftrags-Ausgabe oder eine Vorschau des Auftrags-Ausgabe dar.</span><span class="sxs-lookup"><span data-stu-id="9d816-101">Represents a category of job outputs, such as the main job output, or a preview of the job output.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Custom">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Conventions.Files.JobOutputKind Custom (string text);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind Custom(string text) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Custom(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Custom (text As String) As JobOutputKind" />
      <MemberSignature Language="F#" Value="static member Custom : string -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Custom text" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputKind</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="text" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="text"><span data-ttu-id="9d816-102">Ein Textbezeichner für die benutzerdefinierte JobOutputKind.</span><span class="sxs-lookup"><span data-stu-id="9d816-102">A text identifier for the custom JobOutputKind.</span></span></param>
        <summary>
            <span data-ttu-id="9d816-103">Ruft eine <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> , die eine benutzerdefinierte Kategorie von auftragsausgaben darstellt.</span><span class="sxs-lookup"><span data-stu-id="9d816-103">Gets a <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing a custom category of job outputs.</span></span>
            </summary>
        <returns><span data-ttu-id="9d816-104">Eine JobOutputKind mit dem angegebenen Text.</span><span class="sxs-lookup"><span data-stu-id="9d816-104">A JobOutputKind with the specified text.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="9d816-105"><paramref name="text" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="9d816-105"><paramref name="text" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="9d816-106"><paramref name="text" /> ist leer.</span><span class="sxs-lookup"><span data-stu-id="9d816-106"><paramref name="text" /> is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Equals(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As JobOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; bool" Usage="jobOutputKind.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="9d816-107">Die JobOutputKind dieser Instanz verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d816-107">The JobOutputKind to compare to this instance.</span></span></param>
        <summary>
            <span data-ttu-id="9d816-108">Determinates, ob diese Instanz und ein anderes angegebenes <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> denselben Wert haben.</span><span class="sxs-lookup"><span data-stu-id="9d816-108">Determinates whether this instance and another specified <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> have the same value.</span></span>
            </summary>
        <returns><span data-ttu-id="9d816-109">True, wenn der Wert des der <paramref name="other" /> Parameter ist der Wert dieser Instanz entspricht, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="9d816-109">true if the value of the <paramref name="other" /> parameter is the same as the value of this instance; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="jobOutputKind.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="9d816-110">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d816-110">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="9d816-111">Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.</span><span class="sxs-lookup"><span data-stu-id="9d816-111">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="9d816-112">True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="9d816-112">true if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="jobOutputKind.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d816-113">Gibt den Hashcode für diesen <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="9d816-113">Returns the hash code for this <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />.</span></span>
            </summary>
        <returns><span data-ttu-id="9d816-114">Ein 32-Bit-Hashcode als ganze Zahl mit Vorzeichen.</span><span class="sxs-lookup"><span data-stu-id="9d816-114">A 32-bit signed integer hash code.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobOutput">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobOutput;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobOutput" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly JobOutput As JobOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable JobOutput : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d816-115">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> , die wichtigsten Ausgabe eines Auftrags darstellt.</span><span class="sxs-lookup"><span data-stu-id="9d816-115">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing the main output of a job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreview">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobPreview;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind JobPreview" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly JobPreview As JobOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable JobPreview : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d816-116">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> , die eine Vorschau des Auftrags-Ausgabe darstellt.</span><span class="sxs-lookup"><span data-stu-id="9d816-116">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> representing a preview of the job output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.op_Equality(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (x As JobOutputKind, y As JobOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; bool" Usage="x = y" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="y" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="x"><span data-ttu-id="9d816-117">Die erste JobOutputKind, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d816-117">The first JobOutputKind to compare.</span></span></param>
        <param name="y"><span data-ttu-id="9d816-118">Die zweite JobOutputKind, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d816-118">The second JobOutputKind to compare.</span></span></param>
        <summary>
            <span data-ttu-id="9d816-119">Bestimmt, ob zwei angegebene <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> Instanzen den gleichen Wert aufweisen.</span><span class="sxs-lookup"><span data-stu-id="9d816-119">Determines whether two specified <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> instances have the same value.</span></span>
            </summary>
        <returns><span data-ttu-id="9d816-120">True, wenn der Wert der <paramref name="x" /> entspricht der Wert des <paramref name="y" />, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="9d816-120">true if the value of <paramref name="x" /> is the same as the value of <paramref name="y" />; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind x, class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.op_Inequality(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (x As JobOutputKind, y As JobOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; bool" Usage="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.op_Inequality (x, y)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="y" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="x"><span data-ttu-id="9d816-121">Die erste JobOutputKind, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d816-121">The first JobOutputKind to compare.</span></span></param>
        <param name="y"><span data-ttu-id="9d816-122">Die zweite JobOutputKind, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d816-122">The second JobOutputKind to compare.</span></span></param>
        <summary>
            <span data-ttu-id="9d816-123">Bestimmt, ob zwei angegebene <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> Instanzen über unterschiedliche Werte verfügen.</span><span class="sxs-lookup"><span data-stu-id="9d816-123">Determines whether two specified <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> instances have different values.</span></span>
            </summary>
        <returns><span data-ttu-id="9d816-124">True, wenn der Wert der <paramref name="x" /> unterscheidet sich vom Wert der <paramref name="y" />, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="9d816-124">true if the value of <paramref name="x" /> is different from the value of <paramref name="y" />; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="jobOutputKind.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d816-125">Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt.</span><span class="sxs-lookup"><span data-stu-id="9d816-125">Returns a string that represents the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="9d816-126">Eine Textdarstellung der <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />.</span><span class="sxs-lookup"><span data-stu-id="9d816-126">A textual representation of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>